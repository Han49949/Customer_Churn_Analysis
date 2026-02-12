# Customer Churn Analysis

## Project Overview

This project analyzes telecom customer data to identify churn patterns and build predictive machine learning models.

The objective is to understand customer behavior, identify high-risk churn segments, and provide actionable business insights using data analytics and visualization.

The project includes:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Churn Prediction Modeling
- Power BI Business Dashboard

---

## Dataset

- 7,043 customer records  
- 21+ features including:
  - Demographics (Gender, Senior Citizen, Partner, Dependents)
  - Service Information (Internet Service, Contract, Payment Method)
  - Financial Data (Monthly Charges, Total Charges)
  - Target Variable: Churn Label / Churn Value

---

## Business Objectives

- Calculate overall churn rate
- Identify high-risk customer segments
- Analyze churn by contract type, tenure, payment method, and internet service
- Build a predictive model to classify churn risk
- Provide business-ready dashboard insights

---

## Data Preprocessing

- Removed null values
- Converted Total Charges to numeric
- Encoded categorical variables
- Created Tenure Groups for analysis
- Train-test split (80/20)

---

## Machine Learning Models

### Logistic Regression

- Accuracy: ~76–81%
- ROC-AUC: ~0.77
- Strong baseline classifier

### Random Forest Classifier

- Improved churn recall performance
- Feature importance analysis performed

### Top Important Features

- Total Charges
- Monthly Charges
- Tenure Months
- Internet Service (Fiber optic)
- Contract Type
- Payment Method (Electronic check)

---

## Power BI Dashboard

The interactive dashboard includes:

- Total Customers
- Churned Customers
- Churn Rate (%)
- Average Monthly Charges
- Average Tenure
- Churn by Contract Type
- Churn by Tenure Group
- Churn by Payment Method
- Churn by Internet Service

This enables business stakeholders to quickly identify churn drivers and high-risk segments.

<img width="1158" height="649" alt="image" src="https://github.com/user-attachments/assets/9e268fc0-aea7-45c9-bf7d-a1934c386d82" />

---

## Tools & Technologies

- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib / Seaborn
- Power BI
- Git & GitHub

---

## Key Insights

- Month-to-month contracts show the highest churn rate.
- Customers with fiber optic service churn more frequently.
- Electronic check payment method correlates with higher churn.
- Customers with shorter tenure are significantly more likely to churn.
