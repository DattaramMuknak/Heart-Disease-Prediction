# 📈 Future Price Forecasting using Time Series Analysis

## 📌 Project Overview
This project focuses on forecasting **average monthly prices for the next 12 months** using historical price data.
It applies **time series analysis techniques**, particularly the **SARIMAX (Seasonal ARIMA)** model, to capture trends, seasonality, and temporal dependencies in the data.

The goal is to provide accurate and interpretable forecasts that can assist in **business planning, pricing strategy, and demand forecasting**.

---

## 🎯 Objectives
- Analyze historical monthly price data
- Identify trends and seasonal patterns
- Build a robust time series forecasting model
- Predict prices for the upcoming 12 months
- Evaluate model performance and reliability

---

## 🗂 Dataset
- **Format:** CSV
- **Frequency:** Monthly
- **Target Variable:** Average Monthly Price
- **Index:** Date / Month

---

## 🔍 Data Preprocessing
- Loaded data using **Pandas**
- Converted date column to `datetime`
- Set date as time series index
- Checked and handled missing values
- Split data into training and validation sets

---

## 📊 Exploratory Data Analysis (EDA)
- Time series visualization
- Trend and seasonality analysis
- Rolling mean smoothing
- Seasonal decomposition

---

## 🤖 Model Used
### SARIMAX (Seasonal ARIMA)

SARIMAX(order=(1,1,1), seasonal_order=(1,1,1,12))

---

## 🔮 Forecasting
- Forecast horizon: **Next 12 months**
- Generated monthly future price predictions
- Rounded values for interpretability

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels

---

## 📄 Resume-Ready Summary
Developed a time series forecasting model using SARIMAX to predict average monthly prices, performing data preprocessing, EDA, model training, and future forecasting.

---

## 👤 Author
Sachin Kumar Shah

---

## 📜 License
For educational and portfolio use only.
