# ⏳ Time Series Analysis

## 📌 Overview
This repository contains a collection of Jupyter notebooks showcasing **various time series analysis techniques**.  
It is designed as a reference/tutorial hub for exploring classical statistical methods and modern forecasting techniques.

---

## 📂 Repository Structure
```plaintext
.
├── ACF and PACF.ipynb                        # Plotting autocorrelation and partial autocorrelation
├── AR Model.ipynb                            # Autoregressive model
├── ARMA Model.ipynb                          # Autoregressive Moving Average model
├── AirPassengers.xls                         # Sample monthly passenger dataset
├── ETS.ipynb                                 # Error-Trend-Seasonality model
├── Feature Extraction in time series data.ipynb
├── Moving Average and Exponential Smoothing.ipynb
├── Multivariate Forecasting using Encoder Decoder.ipynb
├── Parameter analysis for ARIMA model.ipynb
├── Practical Time series visualization with python.ipynb
├── Prophet.ipynb                             # Forecasting using Facebook Prophet
├── SARIMA.ipynb                              # Seasonal ARIMA model
├── SARIMAX.ipynb                             # SARIMA with exogenous variables
├── Sliding window, time series to supervised data.ipynb
├── Sorting.ipynb
├── Stationarity.ipynb                        # Stationarity tests and transformations
├── Train Test Split for Time Series.ipynb
├── Trend,Seasonality,Cyclicity,Irregularity,Autocorr.ipynb
├── Weather_data.xls
├── stock_data.xls
└── wind_dataset.xls
```
---
## ⚙️ Methods Covered
- Stationarity testing (ADF, KPSS)
- Autocorrelation & Partial Autocorrelation (ACF/PACF)
- Classical models:
  - AR, MA, ARMA, ARIMA, SARIMA, SARIMAX
  - ETS (Error-Trend-Seasonality)
  - Prophet
- Forecasting techniques:
  - Sliding window to supervised conversion
  - Train-test split strategies for time series
  - Encoder-Decoder models for multivariate forecasting
- Feature extraction from time series data
- Time series decomposition:
  - Trend, seasonality, cyclicity, irregularity
- Visualization & exploratory analysis

---

## 📊 Datasets Included
- `AirPassengers.xls` — Monthly air passenger counts
- `Weather_data.xls` — Sample weather metrics
- `stock_data.xls` — Daily stock market data
- `wind_dataset.xls` — Wind speed dataset

---

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Time-Series-Analysis-.git
   ```
2. Install dependencies (Jupyter + pandas, numpy, statsmodels, prophet, matplotlib, etc.)
3. Open notebooks in Jupyter:
   ```bash
   jupyter notebook
   ```
4. Run any notebook to learn and experiment with the respective technique.

---

## 📌 Key Takeaways
- Covers both **statistical** and **machine learning** approaches to time series
- Shows complete pipeline: data preparation → modeling → evaluation → visualization
- Helpful for students and practitioners learning forecasting and temporal analysis
