# delivery-time-prediction 🚚⏱️

## 📌 Project Overview

This project aims to predict delivery times in a last-mile logistics setting using machine learning models. By analyzing historical delivery data — including weather, traffic, distance, and courier details — we build predictive models to help businesses improve efficiency and customer satisfaction.

---

## 🧠 Objectives

- Predict total delivery time using real-world features
- Analyze the impact of factors like weather, traffic, and vehicle type
- Compare model performance (Random Forest vs. XGBoost)
- Identify key features influencing delivery times

---

## 🗃️ Dataset Description

Each row represents a delivery with the following features:

- `Distance_km`: Distance between pickup and delivery point
- `Weather`: Conditions during delivery (clear, rainy, foggy, etc.)
- `Traffic_Level`: Level of traffic (light, moderate, heavy)
- `Time_of_Day`: Morning, afternoon, evening, etc.
- `Vehicle_Type`: Motorcycle, car, or bike
- `Preparation_Time_min`: Time taken by restaurant
- `Courier_Experience_yrs`: Experience of courier
- `Delivery_Time_min`: 🏁 **Target** variable

---

## 🛠️ Tools & Libraries

- **Python 3**
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `xgboost`

---

## 🔍 Key Steps

1. Data Cleaning & Preprocessing
2. Feature Engineering
3. Model Training:
   - Random Forest
   - XGBoost
4. Performance Evaluation (MAE, RMSE, R²)
5. Feature Importance Analysis

---

## 📈 Results Summary

- Both models show strong predictive ability
- XGBoost slightly outperforms Random Forest in accuracy
- **Distance**, **traffic level**, and **courier experience** are top predictors

---

## 👥 Team

**Dain Lee**  
**Manaswi Kondapally**

DAT402 – Project 2 | Feb 2024

---

