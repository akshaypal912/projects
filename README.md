# 📊 Customer Churn Prediction & Analysis

## 📌 Project Overview
This project focuses on analyzing customer churn behavior and building a machine learning model to predict which customers are likely to leave a telecom service.

The goal is to identify key churn drivers and provide actionable business insights to improve customer retention.

---

## 🎯 Objectives
- Analyze customer data to understand churn patterns  
- Identify key factors affecting customer churn  
- Build a predictive model to classify churn vs non-churn  
- Provide business recommendations to reduce churn  

---

## 📂 Dataset
- Telco Customer Churn Dataset  
- Total Records: ~7000 customers  
- Features include: tenure, monthly charges, contract type, services, payment method, etc.

---

## 🧹 Data Cleaning
- Handled missing values in `TotalCharges`  
- Removed duplicates  
- Converted data types  
- Encoded categorical variables  

---

## 📊 Exploratory Data Analysis (EDA)
Key insights:
- ~50% of churn occurs within the first year  
- Customers with higher monthly charges have higher churn  
- Month-to-month contracts show highest churn  
- Fiber optic users show unexpectedly high churn  
- Customers without tech support/security services churn more  

---

## 🤖 Model Building
- Logistic Regression  
- Random Forest  

### ⚙️ Techniques Used:
- Feature scaling  
- Class imbalance handling (`class_weight='balanced'`)  
- Threshold tuning  

---

## 📈 Model Performance
- Accuracy: ~79%  
- Recall (Churn): Improved using class balancing and threshold tuning  

---

## 💡 Business Insights
- Early customer experience is critical (first-year churn high)  
- Pricing dissatisfaction leads to churn  
- Lack of support services reduces retention  
- Flexible contracts increase churn risk  

---

## 📌 Recommendations
- Improve onboarding and first-year engagement  
- Offer discounts to high-value customers  
- Promote value-added services (tech support, security)  
- Encourage long-term contracts  
- Improve payment experience  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn  

---

