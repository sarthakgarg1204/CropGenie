<h1 align="center">🌾 Crop Genie</h1>

<p align="center">
  <b>Smart Agricultural Recommendation System</b><br>
  Assisting farmers in making informed decisions about crop and fertilizer selection using machine learning.
</p>

---

## ✨ Overview

**Crop Genie** is a powerful tool designed to provide intelligent crop and fertilizer recommendations based on key environmental and soil parameters. The system leverages trained machine learning models to improve agricultural productivity and sustainability.

---

## 🚀 Features

* 🌱 **Crop Recommendation** based on:

  * Nitrogen (N), Phosphorus (P), Potassium (K)
  * Temperature, Humidity
  * Soil pH, Rainfall

* 🧪 **Fertilizer Suggestion** tailored to:

  * Soil nutrients
  * Crop type
  * Environmental conditions

* 🧠 **ML-Powered Backend**:

  * Trained `.sav` models for predictions
  * Scalers for input normalization

---

## 🗂️ Project Structure

```
Crop Genie/
├── crop_model.sav                   # Trained ML model for crop prediction
├── crop_scaler.sav                  # Scaler used for crop input data
├── fertilizer_model.sav             # Trained ML model for fertilizer prediction
├── fertilizer_scaler.sav            # Scaler used for fertilizer input data
├── Crop_Prediction.ipynb            # Main notebook for crop prediction
├── Crop_Prediction_week1.ipynb      # Progress notebook (Week 1)
├── Crop_Prediction_week2.ipynb      # Progress notebook (Week 2)
├── Fertilizer_recommendation.ipynb  # Notebook for fertilizer suggestions
├── Crop_recommendation.csv          # Crop training dataset
├── Fertilizer Prediction.csv        # Fertilizer training dataset
├── Ques_week_1.docx                 # Weekly documentation
└── README.md                        # You are here!
```

---

## 🛠️ Installation & Requirements

> **Python version**: 3.8+

### 🔧 Dependencies

Install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn joblib matplotlib seaborn
```

---

## 🧪 How to Run

1. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

2. **Run Notebooks**:

   * Open `Crop_Prediction.ipynb` for crop prediction.
   * Open `Fertilizer_recommendation.ipynb` for fertilizer recommendations.

3. **Provide Input**:

   * Fill in soil and environmental parameters as prompted in the notebook.
   * Execute cells to get prediction results.

---

## 📊 Datasets

| File Name                   | Description                                 |
| --------------------------- | ------------------------------------------- |
| `Crop_recommendation.csv`   | Training data for crop recommendation       |
| `Fertilizer Prediction.csv` | Dataset for fertilizer recommendation model |

---

## 👥 Team Contributions

This project includes iterative weekly improvements:

* `week1`: Model and EDA initialization
* `week2`: Improved accuracy and functionality

---

## 🔮 Future Enhancements

* 🌐 Web-based frontend for accessibility
* 📱 Mobile app integration with chatbot support
* ☁️ Real-time weather and geolocation data usage
* 📉 Visualization dashboards for farmers

---

## 📃 License

This project is for **academic and educational purposes** only.

---

## 📌 Screenshots (Optional)

> Add images here if you have visuals of the notebook outputs or dashboard UI.
