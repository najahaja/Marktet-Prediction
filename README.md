# Ethereum (ETH/USDT) Price Forecasting using ARIMA

![ETH Price Forecast Example](https://i.imgur.com/XYZ1234.png) *(Replace with your actual forecast plot)*

## 📌 Overview
This project performs **time series analysis** on Ethereum's historical price data (2022-2024) using the **ARIMA (AutoRegressive Integrated Moving Average)** model to forecast future ETH/USDT prices. Key steps include:
- Data collection and preprocessing
- Exploratory Data Analysis (EDA)
- Stationarity testing (ADF Test)
- ARIMA model training and evaluation
- 30-day price forecasting with confidence intervals

## 📊 Key Visualizations
| Diagram | Purpose | Code File |
|---------|---------|----------|
| Historical Price Trends | Identify long-term patterns | [`eda.py`](code/eda.py) |
| Rolling Mean & Volatility | Smooth trends and measure risk | [`rolling_stats.py`](code/rolling_stats.py) |
| ACF/PACF Plots | Determine ARIMA parameters (`p`, `q`) | [`acf_pacf.py`](code/acf_pacf.py) |
| 30-Day Forecast | Predict future prices | [`forecast.py`](code/forecast.py) |



