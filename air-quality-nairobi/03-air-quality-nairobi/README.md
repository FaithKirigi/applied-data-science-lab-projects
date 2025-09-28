# Project 3: Air Quality in Nairobi  

## 🔹 Problem  
Air pollution is a growing concern in Nairobi, with particulate matter and gas emissions affecting both health and quality of life.  
The goal of this project was to **analyze air quality time series data and build models to predict pollutant levels**, using statistical and machine learning techniques.  

---

## 🔹 Approach  

### Lesson 01: Wrangling Data with MongoDB  
- Queried a MongoDB database to extract raw air quality measurements.  
- Transformed and cleaned the data for use in time series analysis.  

### Lesson 02: Linear Regression with Time Series Data  
- Explored linear regression as a baseline for predicting pollutant levels.  
- Incorporated temporal features such as time of day and seasonality.  

### Lesson 03: Autoregressive Models  
- Built an **autoregressive (AR)** model to capture dependencies on past pollutant values.  
- Compared performance against baseline regression.  

### Lesson 04: ARMA Models  
- Extended autoregression to include moving average components (**ARMA model**).  
- Tuned model hyperparameters to improve accuracy.  
- Evaluated performance using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).  

---

## 🔹 Results  
- Successfully wrangled air quality data from MongoDB into a clean time series format.  
- Autoregressive models outperformed linear regression, capturing temporal dependencies in pollutant levels.  
- ARMA models provided further improvements when hyperparameters were tuned.  
- Key insight: Air quality in Nairobi exhibited strong daily and seasonal cycles.  

---

## 🔹 Skills Applied  
- Data Wrangling with **MongoDB**  
- Time Series Analysis (Autoregression, ARMA models)  
- Regression with Temporal Data  
- Hyperparameter Tuning  
- Python (Pandas, NumPy, Statsmodels, Scikit-learn)  

---

## 🔹 Notes  
- Original dataset and notebooks are not shared to comply with **WorldQuant University** guidelines.  
