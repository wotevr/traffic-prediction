

# 🚦 Traffic Flow Prediction using Machine Learning

## 📌 Overview
This project predicts traffic volume using time-based and weather-related features.  
It uses machine learning models to estimate traffic patterns and analyze key influencing factors.

---

## 🎯 Objective
To build a predictive model that estimates traffic volume based on:
- Time of day  
- Day of week  
- Temperature  
- Rainfall  

---

## 📊 Dataset
- Source: Simulated dataset based on real-world traffic patterns  
- Size: 39 data points  
- Features:
  - `date_time`
  - `temp`
  - `rain_1h`
  - `traffic_volume`

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Converted `date_time` into:
  - Hour
  - Day of week  
- Handled missing values using fill methods  

---

### 2. Feature Engineering
- Extracted:
  - Hour → captures peak traffic times  
  - Day → captures weekday/weekend patterns  

---

### 3. Model Used
- Random Forest Regressor  
- Linear Regression (for comparison)

---

## 📈 Evaluation Metrics
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📉 Results
- RMSE ≈ 300 vehicles  
- Model shows reasonable prediction capability for small dataset  
- Random Forest performed better than Linear Regression  

---

## 📊 Visualization
- Actual vs Predicted Traffic Graph  
- Feature Importance Plot  

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

