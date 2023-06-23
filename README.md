# Customer Churn Prediction Model

### This repository contains the code and resources for building a customer churn prediction model for SyriaTel, a telecommunications company. The goal of this project is to accurately predict customer churn and provide insights to help SyriaTel reduce customer attrition.

## Dataset
### The dataset used for training and evaluation consists of historical customer data, including various features that may influence churn behavior. The factors included in the model, ranked in order of their impact, are as follows:

Total Charge on Customer per day
Total minutes a customer used per day
Customer Service Phone Calls
Number of voicemail messages
Total evening charge
Total night charge
Total night minutes
Total international charge
Total international minutes
Total international calls
Total night calls
Account length
Total day calls
Total evening calls

## Model Selection
### After exploring different classification algorithms, the Random Forest classifier was selected as the best model for this task. It exhibited the highest recall score, indicating its ability to correctly identify customers at risk of churn. The model leverages the aforementioned factors to make predictions with a higher accuracy and predictive capability.

