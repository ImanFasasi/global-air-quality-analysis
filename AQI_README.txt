# 🌍 Global Air Quality Analysis

## Overview
This project analyzes air quality data from over 170 countries and 300+ cities, focusing on major pollutants like PM2.5, CO, Ozone, and NO₂. It provides insights into global pollution patterns, identifies dominant pollutants, and builds machine learning models to predict AQI levels.

---

## Objectives
- Understand global air quality trends.
- Identify the most and least polluted cities.
- Analyze relationships between pollutants and overall AQI.
- Predict AQI using pollutant values.
- Provide data-driven recommendations for cleaner air.

---

## Tools & Technologies
- **Python** (Pandas, NumPy, Seaborn, Matplotlib)
- **Scikit-learn** for predictive modeling
- **Jupyter Notebook** for analysis and documentation

---

## Key Insights
- **PM2.5** is the dominant pollutant in most cities and strongly correlates with poor air quality.
- Cities in parts of **India** consistently reported the highest AQI levels.
- Cities with the cleanest air were located in **South America and Southeast Asia**.

---

## Model Performance

**Target:** `aqi_value`  
**Features:** CO, Ozone, NO₂, PM2.5 AQI values

| Model                 | R² Score | MAE  | RMSE |
|----------------------|----------|------|------|
| Linear Regression     | 0.9744   | 4.91 | 9.23 |
| Decision Tree Regressor | 0.9955   | 0.28 | 3.88 |

✅ The **Decision Tree Regressor** provided highly accurate predictions.

---

## Project Structure
