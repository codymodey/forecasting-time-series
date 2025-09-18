# ⏳ Time Series Forecasting – Air Quality & Step Data

This project focuses on **time series forecasting** using both classical and modern approaches.  
The main dataset consists of **PM2.5 air quality measurements** from India, while a small **self-collected dataset of daily step counts** is included for exploratory purposes (EDA only).

The goal is to compare the performance of traditional **ARIMA** models and modern approaches like **Facebook Prophet**, and to demonstrate the workflow of time series analysis, from preprocessing to model evaluation.

---

## 📊 Models Implemented
- **Prophet** – additive model capturing trend, seasonality, and holidays  
- **ARIMA** – classical statistical model for time series  
- **EDA on step count data** – descriptive statistics, visualization, and basic patterns (no forecasting)

---

## 📂 Dataset Sources
- **Air Quality (PM2.5) Dataset**: https://www.kaggle.com/datasets/abhisheksjha/time-series-air-quality-data-of-india-2010-2023
  - Contains hourly PM2.5 concentration data from India (2010–2023)  
  - Used for training and evaluating ARIMA & Prophet models  

- **Self-collected step data**:  
  - Data from a personal step counter (collected with Apple Health)  
  - Only included for **EDA demonstration**, not forecasting  

---

## 🗂 Repository Structure
