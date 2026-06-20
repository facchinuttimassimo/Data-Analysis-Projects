# ARIMA Models for Time Series Analysis

This project analyzes the **Industrial Production Index (IPI)** published by the Federal Reserve, using classical ARIMA models to study the structure of the series and produce short-term forecasts.

The analysis follows a standard Box-Jenkins methodology: stationarity testing, model identification, estimation, and diagnostic checking of residuals.

## Methodology

- **Stationarity testing** — ADF and KPSS tests to check for unit roots
- **Model identification** — ACF and PACF analysis to select ARIMA order
- **Estimation** — Classical ARIMA model fitted via Maximum Likelihood
- **Diagnostics** — Ljung-Box test and residual analysis
- **Forecasting** — Short-term out-of-sample predictions with confidence intervals

## Dataset

- **Source**: Federal Reserve Economic Data (FRED)
- **Series**: Industrial Production Index (IPI)
- **Frequency**: Monthly
