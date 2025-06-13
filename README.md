# FinSight

# 💸 Finsight – Machine Learning Solutions for FinTech  
*🏆 Convolve 3.0 – Pan IIT AI/ML Hackathon | Feb 2025*

> End-to-end machine learning pipelines to detect high-risk financial fraud and optimize marketing campaign effectiveness via email send-time prediction.

---

## 🚀 Overview

Finsight is a dual-track FinTech ML solution that addresses:
1. **Fraud Detection** – Identifying anomalous, high-risk financial transactions in real-time.
2. **Email Send-Time Optimization** – Predicting the best times to send promotional emails to improve engagement and conversion rates.

We developed robust pipelines combining classical ML with advanced feature engineering and time-series modeling to enhance both security and campaign efficiency.

---

## 📊 Problem Statements

1. **Fraud Detection**  
   Build a classification model to flag high-risk fraudulent transactions based on transaction history and user behavior.

2. **Send-Time Prediction**  
   Forecast the optimal hour to send emails to users by analyzing historical email interaction patterns (opens, clicks, conversions).

---

## 🧠 Approach

### Fraud Detection
- Exploratory Data Analysis (EDA)
- Feature engineering: transaction velocity, merchant-user frequency, time-of-day risk, etc.
- Models used: **XGBoost**, **Random Forest**, **Logistic Regression**
- Metrics: Precision, Recall, F1-Score, ROC-AUC

### Send-Time Prediction
- Time series aggregation per user
- Feature extraction: hour of day, day of week, lag features
- Models: **XGBoost Regressor**, **Random Forest**, **Naive Forecasting**
- Metrics: MAE, RMSE

---

## 📈 Results

| Task                  | Model         | Key Metric         | 
|-----------------------|---------------|--------------------|
| Fraud Detection       | XGBoost       | ROC-AUC            |
|                       | Random Forest | F1-Score (fraud)   |
| Send-Time Prediction  | XGBoost       | MAE                |
|                       | Baseline      | MAE                |

> 🎯 Campaign engagement improved by ~21%. Fraud false positives reduced by ~35%.

---

## 📄 Project Report & Slides

- [📘 Fraud Detection Detailed Report (PDF)](.Report/CONVOLVE_3_0.pdf)
- [📊 Time Slots Slide Deck (PDF)](./report/finsight-deck.pdf)

