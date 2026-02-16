# 🌦️ Weather Trend Forecasting — Ottawa (Basic Assessment)

## 📌 Project Overview

This project analyzes weather data from the **Global Weather Repository** dataset to explore weather trends and build a basic forecasting model.

The analysis focuses on **Ottawa, Canada**, and demonstrates the essential data science workflow including:

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Visualization of weather trends
- Basic Time Series Forecasting

The `last_updated` feature is used as the primary time component for time-series analysis.

---

## 🎯 Objective

The goal of this project is to:

- Handle missing values and outliers
- Normalize data where needed
- Explore temperature and precipitation patterns
- Build and evaluate a basic forecasting model

---

## 🌍 PM Accelerator Mission

> PM Accelerator’s mission is to break down barriers to opportunity by providing accessible education, mentorship, and practical project experience that helps individuals build real-world skills.

---

## 📊 Dataset

**Source:** Kaggle  
Global Weather Repository  
https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository

---

## 🧹 Data Cleaning & Preprocessing

1. Converted `last_updated` to datetime format.
2. Filtered data for **Ottawa**.
3. Aggregated multiple hourly records into daily data:
   - Temperature → daily mean
   - Precipitation → daily sum
4. Handled missing dates using reindexing.
5. Filled missing values using interpolation + forward/backward fill.
6. Outliers handled using the IQR method.
7. Applied MinMax normalization for modeling.

---

## 📈 Exploratory Data Analysis (EDA)

- Daily temperature trend visualization
- Daily precipitation trend visualization
- Correlation analysis between weather features

---

## 🤖 Forecasting Model

Baseline time-series model:
- Naive Forecast (Lag-1)

Evaluation:
- MAE
- RMSE
- MAPE

---

## 📁 Project Structure

```
World-Weather-Repository/
│
├── World_Weather_Repository_FINAL.ipynb
├── README.md
└── data/
```

---
