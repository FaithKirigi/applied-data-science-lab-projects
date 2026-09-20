# Project 8: Volatility Forecasting in India  

## 🔹 Problem  
Volatility measures how much financial asset returns fluctuate over time and is an important component of investment and risk-management decisions.  
The goal of this project was to **build and deploy a time-series model for forecasting the volatility of an Indian financial asset** using historical market data and a GARCH model.  

---

## 🔹 Approach  

### Lesson 1: Financial Data Collection  
- Retrieved historical market data from an external financial-data API.  
- Built a reusable Python class to request, clean, and validate the market data.  
- Converted historical asset prices into returns for volatility analysis.  

### Lesson 2: SQL Data Storage  
- Created a SQL database for storing the collected market data.  
- Built a repository class to insert new observations and retrieve historical records.  
- Connected the data-collection process to the database to create a reproducible data pipeline.  

### Lesson 3: GARCH Modelling  
- Explored the return series and identified periods of volatility clustering.  
- Built a **Generalized Autoregressive Conditional Heteroskedasticity (GARCH)** model to estimate changing volatility over time.  
- Evaluated model performance using statistical diagnostics and generated future volatility forecasts.  

### Lesson 4: Model Deployment  
- Combined the data-collection, database, and forecasting components into a reusable application.  
- Developed an API through which the model could be trained and volatility forecasts requested.  
- Structured the application so that new market data could be collected and used to update the model.  

---

## 🔹 Results  
- Built a complete data pipeline for retrieving, cleaning, and storing historical financial-market data.  
- Identified volatility clustering in the asset-return series, supporting the use of a GARCH model.  
- Generated short-term forecasts of expected market volatility.  
- Successfully integrated data collection, SQL storage, time-series modelling, and API deployment into one forecasting system.  

---

## 🔹 Skills Applied  
- Python  
- Financial Data Analysis  
- API Data Collection  
- Object-Oriented Programming  
- SQL Database Management  
- Time-Series Analysis  
- Financial Return Calculations  
- GARCH Modelling  
- Volatility Forecasting  
- Model Diagnostics and Deployment  
- API Development  

---

## 🔹 Notes  
- Original dataset and notebooks are not shared to comply with **WorldQuant University** guidelines.  
