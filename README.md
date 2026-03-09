# Customer Churn Prediction

## Project Overview
Customer churn is a major challenge for telecom companies because acquiring new customers is significantly more expensive than retaining existing ones. This project focuses on predicting whether a customer is likely to churn using machine learning techniques.

The objective of this project is to analyze customer behavior and build a predictive model that helps businesses identify customers who are at high risk of leaving the service. By predicting churn in advance, companies can implement targeted retention strategies.

The project also includes an interactive web application built using Streamlit where users can input customer details and get real-time churn predictions.

---

## Dataset Summary
The dataset used in this project contains telecom customer information such as demographic details, service subscriptions, account information, and billing data.

Key dataset characteristics:

- Total Customers: ~7000+
- Features: 20+ customer attributes
- Target Variable: Churn (Yes / No)

Important features include:

- Customer demographics (Gender, Senior Citizen)
- Account information (Tenure, Contract type)
- Service usage (Internet Service, Phone Service)
- Billing details (Monthly Charges, Total Charges)

The dataset helps understand customer behavior and identify patterns that contribute to churn.

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Streamlit
- Jupyter Notebook

---

## Project Workflow

1. **Data Collection**
   - Imported the telecom churn dataset.

2. **Data Cleaning**
   - Handled missing values.
   - Converted data types where necessary.

3. **Exploratory Data Analysis (EDA)**
   - Analyzed customer distribution.
   - Studied relationships between features and churn.
   - Identified patterns in customer behavior.

4. **Data Preprocessing**
   - Label encoding of categorical variables.
   - Feature selection.

5. **Model Building**
   - Implemented a Random Forest Classifier to predict churn.

6. **Model Evaluation**
   - Evaluated model performance using accuracy and classification metrics.

7. **Model Deployment**
   - Built an interactive web application using Streamlit for real-time churn prediction.

---

## Key Insights

- Customers with **higher monthly charges** tend to churn more frequently.
- **Short tenure customers** are more likely to leave the service.
- Customers using **fiber optic internet service** showed higher churn rates.
- Customers without **long-term contracts** are more likely to churn.

These insights help businesses understand which customer segments require attention.

---

## Business Impact

Predicting customer churn can significantly help telecom companies improve their customer retention strategies.

Benefits include:

- Identifying high-risk customers early
- Implementing targeted retention campaigns
- Reducing revenue loss due to churn
- Improving customer satisfaction

This predictive system allows businesses to make **data-driven decisions** to retain valuable customers.
