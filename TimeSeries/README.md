# 📈 Time Series Analysis: Ad Spend & Page Views

## 📁 Project Description
The project aims to analyze and forecast web traffic (viewer count) over time and evaluate the impact of advertising spending. Time series models such as **ARIMA**, **SARIMA** and **SARIMAX** are employed to capture both seasonality and exogenous effects.

## 🔍 Methodology
- **Data preprocessing**: Missing values, outlier detection
- **Exploratory Data Analysis (EDA)**: Trend, seasonality, and autocorrelation plots.
- **Stationarity Testing**: ADF test.
- **Modeling**:
  - **SARIMA**: Seasonal ARIMA model for baseline time series modeling.
  - **SARIMAX**: Seasonal ARIMA with exogenous variable (ad cost).
- **Model Diagnostics**: Residual analysis, white noise check, overfitting.
- **Forecasting**: 15 days and 30 days.
