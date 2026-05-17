# 📊 Telco Customer Churn Analysis (EDA + Data Cleaning)

## 📌 Project Overview
This project focuses on analyzing customer churn behavior using the Telco Customer Churn dataset. The goal is to clean the data, explore key patterns, and prepare it for future machine learning modeling.

---

## 📂 Dataset Information
The dataset includes:
- Customer demographics (gender, senior citizen, partner, dependents)
- Services (internet, phone, streaming services)
- Account details (tenure, monthly charges, total charges)
- Target variable: **Churn (Yes/No)**

---

## 🧹 Data Cleaning Steps
- Converted `TotalCharges` from object to numeric
- Handled missing values using median imputation
- Removed leading/trailing whitespace in categorical columns
- Checked and removed duplicate records
- Dropped `customerID` (non-predictive identifier)
- Encoded target variable (Churn → 0/1)

---

## 📊 Exploratory Data Analysis (EDA)
The following analyses were performed:
- Churn distribution analysis
- Correlation heatmap of numerical features
- P-value significance testing
- Tenure vs churn relationship
- Monthly charges vs churn behavior
- Outlier detection in numeric variables

---

## ⚖️ Class Imbalance
The dataset shows class imbalance:
- Non-Churn: ~73%
- Churn: ~27%

To handle this, **stratified sampling will be used in model training**.

---

## 📈 Key Insights
- Customers with lower tenure are more likely to churn
- Higher monthly charges slightly increase churn probability
- Contract type plays a major role in retention
- Payment method affects churn behavior

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- SciPy

---

## 🚀 Future Work
- Build machine learning classification models
- Handle class imbalance using SMOTE or class weights
- Evaluate models using ROC-AUC and F1-score

---

Machine Learning Project
