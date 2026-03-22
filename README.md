# Telco Customer Churn Prediction with XAI

Churn prediction for a telecom dataset, with a focus on explainability. The model flags customers likely to leave; SHAP tells you why.

The end result is a Streamlit app where you drop in a customer profile and get back a churn probability alongside a SHAP waterfall chart breaking down which features drove that prediction.

## Dataset

IBM Telco Customer Churn, publicly available on Kaggle:  
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

After downloading, place the CSV file inside `data/raw/`.

## Stack

- Python, scikit-learn, XGBoost, imbalanced-learn, SHAP, Streamlit

## Status

Work in progress