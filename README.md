# Delhi AQI Forecasting Project

This project aims to analyze and forecast the Air Quality Index (AQI) of Delhi using both Time Series and Machine Learning models. The goal is to understand air pollution trends and predict future AQI levels for better environmental planning and health awareness.

---

## 📌 Overview

- 📅 **Dataset**: Daily AQI data for Delhi (2015–2020)
- 🧠 **Models Used**:
  - SARIMA (Seasonal ARIMA)
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - Gradient Boosting with GridSearchCV (Tuned Model)
- 🎯 **Goal**: Forecast AQI levels and evaluate the performance of different predictive models

---

## 📊 AQI Over Time

Visualizing AQI trends in Delhi from 2015 to 2020:

![Delhi AQI Over Time](aqi_timeseries.png)

---

## ⏱️ Time Series Forecasting (SARIMA)

Forecasting the next 30 days of AQI using SARIMA:

![SARIMA Forecast](sarima_forecast.png)

---

## 🤖 Machine Learning Model Comparison

Comparing performance of various ML models using R² scores:

![Model Comparison](model_comparison.png)

---

## 📈 Results

- All models performed well, with **Gradient Boosting** showing the highest predictive power.
- **SARIMA** effectively modeled seasonal trends in AQI for short-term forecasting.

---

## 🛠️ Tools & Libraries

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- statsmodels (SARIMA)  
- Jupyter Notebook  

---

## 📂 Project Structure

```bash
📁 aqi-forecasting-delhi/
├── aqi_forecasting.ipynb         # Main Jupyter Notebook
├── README.md                     # Project overview
├── aqi_timeseries.png            # AQI over time plot
├── sarima_forecast.png           # SARIMA forecast plot
└── model_comparison.png          # ML model performance comparison
