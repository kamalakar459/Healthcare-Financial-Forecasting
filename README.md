CVS Health Stock Forecasting Project
This project analyzes CVS Health (CVS) stock data and builds a forecasting model to predict future stock prices.  
It combines exploratory data analysis (EDA) with time-series forecasting (ARIMA) to provide insights into historical patterns and future trends.  
Project Workflow
1. Data Collection 
   - Downloaded 5 years of historical stock data using `yfinance`.  
2. Exploratory Data Analysis (EDA)  
   - Visualized price trends, moving averages, and trading volume.  
   - Analyzed daily returns and stock volatility.  
3. Forecasting with ARIMA
   - Built an ARIMA model to predict stock prices for the next 90 business days.  
4. Model Evaluation
   - Split data into training (80%) and testing (20%).  
   - Evaluated using RMSE and **MAPE.  
---
 Results

- RMSE: ~ _X.XX USD_  
- MAPE: ~ _Y.YY%_  
- Forecast shows a stable but slightly fluctuating trend in CVS prices.  

---

 Tech Stack

- Python 3
  Libraries: 
  - `yfinance` → stock data download  
  - `pandas`, `numpy` → data handling  
  - `matplotlib` → visualization  
  - `statsmodels` → ARIMA forecasting  
  - `scikit-learn` → evaluation metrics  





