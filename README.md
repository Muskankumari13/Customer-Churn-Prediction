# Customer Churn Prediction

A machine learning project that predicts telecom customer churn using an 
Artificial Neural Network built with TensorFlow and Keras.

---

## Problem Statement

Telecom companies lose significant revenue due to customer churn. 
This project builds a predictive model to identify at-risk customers 
before they leave, enabling targeted retention strategies.

---

## Dataset

- **Source:** IBM Telco Customer Churn Dataset
- **Size:** 7,043 customer records
- **Features:** 21 features including demographics, account information, 
and service usage patterns

---

## Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Deep Learning | TensorFlow, Keras |
| Visualization | Matplotlib, Seaborn |

---

## Approach

1. Data cleaning and handling missing values
2. Feature engineering and one-hot encoding of categorical variables
3. Feature scaling using StandardScaler
4. Built and trained an ANN with multiple dense layers
5. Model evaluation using accuracy, precision, recall, and confusion matrix

---

## Results

| Metric | Score |
|---|---|
| Test Accuracy | 80.06% |
| Dataset Size | 7,043 records |
| Model Type | Artificial Neural Network (ANN) |

---

## Project Structure

Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb   # Main notebook
├── WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dataset
└── README.md
