# Telco Customer Churn Analysis & Prediction

This project analyzes customer churn patterns from the telecommunications company 'Telco' and builds a predictive model to identify customers who are likely to cancel their service. It includes exploratory data analysis (EDA), feature engineering, and a logistic regression model to assist with customer retention strategies.

---

## Project Objectives

- Identify patterns and drivers of customer churn using real world telecom data.
- Visualize trends across tenure, contract types, monthly charges, and more.
- Build a predictive model to flag high-risk churn customers.
- Provide actionable business recommendations based on data insights.

---

## Dataset

- **Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Records:** 7,043 customers
- **Target Variable:** `Churn` (Yes/No)

---

## Exploratory Data Analysis Highlights

- Customers with **month-to-month contracts** are significantly more likely to churn.
- **High monthly charges** correlate slightly with churn.
- **Tenure** is the strongest predictor: customers who churn tend to have lower tenure.
- Churn is less common among customers with **long-term contracts** or high `TotalCharges`.

---

## Model Summary

- **Model Used:** Logistic Regression
- **Accuracy:** 72%
- **Precision (Churn):** 49%
- **Recall (Churn):** 79%
- **F1 Score (Churn):** 61%

> The model provides a reasonable (but not effective) starting point for identifying customers at risk of churning, especially when combined with business rules.

---

## Business Recommendations

- Focus retention efforts on **new customers** and those on **month-to-month contracts**.
- Offer incentives for long-term contracts (e.g., annual discounts or bundles).
- Use predictive scoring to prioritize high-paying customers for outreach.
- Improve early customer experience (onboarding, follow-ups) to reduce churn in the first 6 months.

---

## Tools Used

- **Python**: pandas, numpy, seaborn, matplotlib, scikit-learn
- **Jupyter Notebook**: for step-by-step analysis and modeling

---
