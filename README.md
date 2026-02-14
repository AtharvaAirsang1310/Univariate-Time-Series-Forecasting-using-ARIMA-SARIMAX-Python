# 🛒 Grocery Store Sales Forecasting – Time Series Analysis

## 📌 Project Overview
This project focuses on analyzing and forecasting grocery store sales using Time Series techniques in Python.  
The aim is to identify trends, seasonality, and predict future sales to support better inventory and business planning.

---

## 🎯 Objectives
- Understand historical grocery sales patterns  
- Detect seasonal trends and demand fluctuations  
- Build forecasting models  
- Compare ARIMA and SARIMAX performance  
- Predict future monthly sales  

---

## 🗂️ Dataset
- Contains historical grocery store sales data with date and sales columns  
- Structured for time-series forecasting  
- Used for training and evaluating predictive models  

---

## 🧹 Data Cleaning
- Converted date column to datetime format  
- Set date as index  
- Checked missing/null values  
- Verified stationarity  
- Split dataset into training and testing sets  

---

## 🔍 Exploratory Data Analysis (EDA)
- Line plots to observe monthly sales trends  
- Seasonal decomposition to detect recurring patterns  
- Identified peak and low sales periods  

---

## 🤖 Models Used

### ARIMA
- Baseline forecasting model  
- Struggled to capture seasonality fully  

### SARIMAX
- Included seasonal parameters  
- Produced more accurate and realistic predictions  
- Better alignment with actual sales data  

---

## 📊 Visualizations
- Actual vs Predicted Sales Graphs  
- Seasonal Decomposition Plots  
- Future Forecast Charts  

---

## 🔑 Key Findings
- Grocery sales show strong seasonal behavior  
- ARIMA underperformed in seasonal periods  
- SARIMAX handled seasonality effectively  
- Forecasting helps improve inventory planning and revenue prediction  

---

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Statsmodels  

---

## 🚀 Conclusion
The SARIMAX model outperformed ARIMA by accurately capturing seasonal trends in grocery sales data.  
Time series forecasting proves valuable for business decision-making, demand planning, and stock optimization.

---
