# Air Quality Prediction Project 🌎

This repository contains the code and analysis for predicting air quality using machine learning techniques. The goal of this project is to build a model that accurately predicts air quality based on various environmental factors.

---

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#modeling)
- [Results](#results)

---

## Overview
Air quality has a significant impact on health and the environment. This project leverages machine learning to predict air quality levels using historical data. By analyzing trends and training a robust regression model, we aim to better understand factors affecting air quality and improve monitoring systems.

---

## Technologies Used
- **Python**  
  - Libraries: `pandas`, `matplotlib`, `seaborn`, `sklearn`
- Machine Learning Algorithm: `RandomForestRegressor`


---

## Exploratory Data Analysis (EDA)
Key steps performed in EDA:
- Analyzed patterns, correlations, and distributions in the data.
- Visualized trends using **Seaborn** and **Matplotlib**.
- Identified and handled any missing or outlier values to ensure data quality.

---

## Modeling
The model was built using a **Random Forest Regressor** to predict air quality. Key steps include:
1. **Data Preprocessing**:  
   - Standardized features using `StandardScaler`.
   - Split the data into training and testing sets using `train_test_split`.

2. **Model Training**:  
   - Used the **RandomForestRegressor** to train on the processed dataset.

3. **Evaluation Metrics**:  
   - **Mean Squared Error (MSE)**: `23.22`
   - **R² Score**: `0.9974`

---

## Results
The model achieved outstanding results:
- **MSE**: *23.22*  
- **R² Score**: *0.9974*  

This indicates the model explains 99.7% of the variance in air quality levels, showcasing its accuracy and reliability.


