# 📊 Customer Churn Prediction with PySpark

This project demonstrates how to use **PySpark** (Apache Spark’s Python API) to build a **customer churn prediction pipeline**.  
We use the **Telco Customer Churn dataset** to predict whether a customer will leave (churn) based on their demographics, contract type, and service usage.

---

## 🚀 Project Overview
- Built an **end-to-end data pipeline** in PySpark covering data loading, cleaning, feature engineering, model training, and evaluation.  
- Trained a **Logistic Regression model** using Spark MLlib with an **AUC of ~0.80** on test data.  
- Derived **business insights** on churn patterns (e.g., by contract type, payment method, monthly charges).  
- Designed with scalability in mind — handles large datasets with distributed processing.  

---

## 🗂 Dataset
We used the **Telco Customer Churn dataset** originally from [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn).  
For convenience, you can download a public copy used here:

```bash
wget -O Telco-Customer-Churn.csv https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv
