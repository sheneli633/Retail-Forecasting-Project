## 📊 Retail Demand Forecasting in R

### Overview
This project develops time-series forecasting models to predict monthly US clothing retail sales using data from the Federal Reserve Economic Data (FRED) database. The goal is to evaluate forecasting approaches and generate insights to support retail planning decisions.

---

### Tools & Methods
- R (`fpp3`, `tsibble`, `fable`)
- Time series visualization and STL decomposition
- Log transformation and seasonal differencing
- ARIMA and ETS models
- Forecast evaluation (RMSE, MAE)
- Residual diagnostics (Ljung–Box test)

---

### Key Results
- ARIMA models outperformed ETS in both accuracy and residual diagnostics  
- Strong seasonal patterns observed, with consistent peaks during holiday periods  
- Final model produced reliable short-term forecasts  

---

### Business Insights
- Retail demand shows predictable seasonal spikes during holiday periods  
- Forecasts can support:
  - inventory planning  
  - staffing decisions  
  - promotional timing  

---

### Files
- `retail_forecasting.qmd` – analysis code  
- `retail_forecasting.html` – final report 
