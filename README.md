# 🧪 Analyzing the Trends of COVID-19 with Python

This project explores the global and national trends of the COVID-19 pandemic using real-world data. It includes data cleaning, visualization, and time-series forecasting using machine learning and statistical models.

## 📂 Dataset

- **Source**: Google Drive CSV
- **Contents**: Daily confirmed, deaths, recovered, and active cases
- **Coverage**: Global data with detailed records for India
- **Last Date in Dataset**: July 27, 2020

## 🎯 Objectives

- Analyze COVID-19 trends globally and for India
- Visualize infection, recovery, and mortality rates
- Forecast future case numbers using time-series models

## 🛠️ Technologies Used

- **Python Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `prophet`, `statsmodels`, `sklearn`
- **Models**: Facebook Prophet, ARIMA, SARIMA
- **Visualization**: Line plots, choropleth maps, rolling statistics

## 🔍 Key Steps

1. **Data Preprocessing**
   - Null and duplicate handling
   - Column renaming and formatting
2. **Exploratory Data Analysis**
   - Top affected countries
   - Time-series trends
   - Geospatial mapping
3. **Forecasting**
   - Prophet model for short-term prediction
   - ARIMA and SARIMA for statistical modeling
   - Stationarity testing and log transformation

## 📈 Visualizations

- Line plots of confirmed cases over time
- Choropleth map of active cases by country
- Rolling mean and standard deviation plots
- Forecast plots from Prophet, ARIMA, and SARIMA

## 📊 Forecasting

- **Prophet**: 7-day forecast
- **ARIMA/SARIMA**: Model tuning using RMSE
- **Future Prediction**: Extended forecasting for up to 5 years (60 months)

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly prophet statsmodels scikit-learn
