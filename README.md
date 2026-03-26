# Applied Time Series Analysis: US Unemployment Rate Forecasting

This repository contains a comprehensive statistical analysis of the U.S. Unemployment Rate. The project applies Time Series methodologies to model historical trends and generate reliable future forecasts using R.

## 🎯 Project Objective
The goal was to identify the best-fitting stochastic model for the monthly unemployment rate (Series ID: LNS14000006). By analyzing historical data, I built a predictive framework that captures the cyclical and seasonal nature of the labor market.

## 💡 Methodology
I followed a structured econometric approach to ensure model robustness:

* **Stationarity & Differencing:** Conducted unit root tests (ADF/KPSS) to determine the necessary order of integration for the series.
* **Model Identification:** Analyzed ACF and PACF plots to identify potential AR and MA components.
* **SARIMA Modeling:** Developed and compared multiple Seasonal ARIMA models to account for the intrinsic seasonality of unemployment data.
* **Diagnostics:** Performed residual analysis (White Noise tests, Ljung-Box) and normality checks to validate the model's integrity.
* **Forecasting:** Generated out-of-sample forecasts to visualize the projected path of the unemployment rate with 80% and 95% confidence intervals.

## 🛠️ Tech Stack
* **Language:** R
* **Core Libraries:** `forecast`, `tseries`, `ggplot2`, and `stats`.

## 📂 Repository Structure
* **Analysis_Report.pdf**: The final paper detailing the statistical theory, model selection process, and economic interpretation.
* **Analysis_Source.Rmd**: The complete R Markdown script for full reproducibility of the results.
* **LNS14000006.csv**: The raw time series dataset.

## 📈 Key Findings
The final model effectively captures the mean-reverting behavior of the unemployment rate while adjusting for seasonal shocks. This project demonstrates a deep dive into the mathematical complexities of time-dependent data and its practical application in economics.
