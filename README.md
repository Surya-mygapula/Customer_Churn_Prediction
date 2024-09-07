# Customer_Churn_Prediction
## Overview
This project involves a machine learning model designed to predict customer churn based on various features. The model uses a Random Forest Classifier to identify whether a customer will churn or remain with the company. 

## Dataset
The dataset used is `Churn_Modelling.csv`, which contains customer information and churn labels. Key features include:

- **Geography**: The location of the customer (e.g., France, Germany, Spain).
- **Gender**: Gender of the customer.
- **NumOfProducts**: Number of products the customer has.
- **HasCrCard**: Whether the customer has a credit card (1 for Yes, 0 for No).
- **IsActiveMember**: Whether the customer is an active member (1 for Yes, 0 for No).

## Project Structure
- `churn_prediction.py`: Script for loading data, training the model, and making predictions.
- `Customer_Churn_Prediction.pkl`: Saved Random Forest model.
- `StandardScaler.pkl`: Saved StandardScaler object for data preprocessing.
