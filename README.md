# 📊 Retail Demand Forecasting in R

## Overview
This project develops time-series forecasting models to predict monthly US clothing retail sales using data from the Federal Reserve Economic Data (FRED). The goal is to evaluate forecasting approaches and generate insights to support retail planning decisions.

---

## Key Results
- ARIMA models outperformed ETS in both forecast accuracy and residual diagnostics  
- Strong seasonal demand patterns observed, with peaks during holiday periods  
- Final model provides reliable short-term forecasts for retail planning  

---

## Business Impact
The forecasts highlight predictable seasonal demand spikes, which can support:
- inventory planning  
- staffing decisions  
- promotional timing  

---

## Methodology
- Log transformation for variance stabilization  
- Seasonal differencing based on ACF analysis  
- ARIMA and ETS model comparison  
- Forecast evaluation using RMSE and Ljung–Box test  

---

## Final Model
The selected ARIMA model achieved the best balance of accuracy and well-behaved residuals, indicating it effectively captures the underlying time-series structure.

---

## Files
- `retail_forecasting.qmd` – analysis code  
- `retail_forecasting.html` – final report 
