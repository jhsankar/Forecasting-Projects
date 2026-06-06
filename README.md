
# Time Series Forecasting Projects

This repository contains two applied time-series forecasting assignments completed as part of my forecasting coursework. The projects demonstrate exploratory time-series analysis, backtesting, and forecast evaluation using real-world economic and business datasets.

## Projects

### 1. AAPL Stock Price Forecasting with Macroeconomic Indicators

This project analyzes monthly Apple stock prices from 2015–2024 alongside three U.S. macroeconomic indicators:

- Consumer Price Index (CPI)
- Unemployment Rate
- Federal Funds Rate

The analysis includes time-series visualization, correlation analysis, scatter plots, and ETS-based forecasting. Multiple ETS model specifications were compared using a 12-month holdout test set.

**Best model:** ETS(M,M,N)  
**MAPE:** 7.23%  
**Methods:** ETS forecasting, correlation analysis, holdout validation, RMSE/MAE/MAPE/MASE/MdAPE evaluation

---

### 2. Australian Anti-Diabetic Drug Sales Forecasting

This project forecasts monthly anti-diabetic drug sales in Australia using ETS and ARIMA-family models. The series shows a strong upward trend and multiplicative seasonality, making it useful for comparing additive and multiplicative forecasting approaches.

The analysis includes decomposition, stationarity testing, ACF/PACF diagnostics, and walk-forward backtesting across four 12-month test periods.

**Best model:** ETS(M,Md,M)  
**Average MAPE:** 6.15%  
**Methods:** ETS, SARIMA, Auto ARIMA, seasonal decomposition, ADF/KPSS tests, walk-forward backtesting

## Skills Demonstrated

- Time-series visualization
- Forecast model selection
- ETS modeling
- SARIMA and Auto ARIMA
- Seasonal decomposition
- Stationarity testing
- ACF/PACF diagnostics
- Backtesting
- Forecast accuracy evaluation
- Python, pandas, statsmodels, pmdarima, scikit-learn, matplotlib

## Repository Contents

```text
aapl_stock_price_forecasting.ipynb
forecasting_anti_diabetic_drug_sales.ipynb
README.md
