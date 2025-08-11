**Gold Price Forecasting**
**Project Summary**
This project applies time series and machine learning techniques to forecast weekly gold prices from 2017 to 2023. The goal was to explore model performance under volatile financial market conditions and determine the most suitable forecasting approach.

**Approach**
Data Preparation – Cleaned and structured 312 weekly gold price records, handled missing values, and analysed trends, seasonality, and volatility patterns.

Model Development – Implemented ARIMA, Holt’s Linear, Holt-Winters, and Random Forest models. Parameters were optimised using ADF tests, ACF/PACF analysis, and diagnostic checks.

Model Evaluation – Compared models using RMSE, AICC, and BIC to assess accuracy and generalisability.

**Key Insights**
Given the highly volatile nature of gold prices, most models struggle to consistently follow rapid fluctuations. 
TES and DES models show relatively smoother fitting curves that adapt well to short-term trends. 
ARIMA captures the overall level effectively but appears less responsive to sharp movements. 
In contrast, the Random Forest (RF) model overfits the recent data with excessive fluctuations, making it less suitable for modelling such erratic time series.

**Tools & Libraries**
Python, Pandas, NumPy, Matplotlib, Statsmodels, Scikit-learn
