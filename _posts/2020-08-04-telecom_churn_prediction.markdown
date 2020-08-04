---
layout: post
title:      "Telecom Churn Prediction"
date:       2020-08-04 14:32:20 +0000
permalink:  telecom_churn_prediction
---


Complete Blog in the url below:

https://medium.com/@khuloodnasher72/telecom-churn-prediction-c5cb9dbdfb66

Introduction
What is Customer Churn? Customer churn or customer attrition is the loss of customers by a business when customers stop using the service of the company. We calculate the churn rate by dividing the number of customers that were lost during that time by the number of customers that existed at the beginning of that time.
Why is it important to calculate customer churn?
Because business is built on several customers using its service. Keeping its customers is less expensive than bringing new ones.
More Important Questions:
In this project, I tried to figure out the answers to the following important questions:
Q1: What percentage of customers churn?
Q2: What are the common variables among churn customers?
Q3: What is the predicted percentage of customer churn?
Q4: How to reduce customer churn?
To answer these questions, I followed a data science process of the project cycle i.e. well known as OSMEN where I tried to predict the customers who have a high probability to churn and help to set recommendations to keep them.
Image for post
About Telco data
Data were obtained from https://www.kaggle.com/dpr1988/telecom-churn-dataset
Each row represents a customer, and each column contains the customer’s attributes described in the column Metadata.
The raw data contains 7043 rows which are customers and 21 columns that are features.
The “Churn” column is our target.
Customer ID is a unique value and has 7043 inputs.
gender: Whether the customer is a male or a female.
Senior citizen: Whether the customer is a senior citizen or not (1, 0)
Partner: Whether the customer has a partner or not (Yes, No)
Dependents: Whether the customer has dependents or not (Yes, No)
tenure: Number of months the customer has stayed with the company
PhoneService: Whether the customer has a phone service or not (Yes, No)
MultipleLines: Whether the customer has multiple lines or not (Yes, No, No phone service)
InternetService: Customer’s internet service provider (DSL, Fiber optic, No)
OnlineSecurity: Whether the customer has online security or not (Yes, No, No internet service)
OnlineBackup: Whether the customer has an online backup or not (Yes, No, No internet service)
DeviceProtection: Whether the customer has device protection or not (Yes, No, No internet service)
TechSupport: Whether the customer has tech support or not (Yes, No, No internet service)
StreamingTV: Whether the customer has streaming TV or not (Yes, No, No internet service)
StreamingMovies: Whether the customer has streaming movies or not (Yes, No, No internet service)
Contract: The contract term of the customer (Month-to-month, One year, Two years)
PaperlessBilling: Whether the customer has paperless billing or not (Yes, No)
PaymentMethod: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
MonthlyCharges: The amount charged to the customer monthly
TotalCharges: The total amount charged to the customer
Churn: Whether the customer churned or not (Yes or No)
Explore Data
I investigated every categorical column and I visualized it and I studied every numeric column and I visualized it. To see my project, please click here.
So first, I explored the target column through the pie plot.
Image for post
Image for post
Through Exploring the target,’churn’ column, we can see that we have an imbalance target because of approximately 73% of “No”, and 27% of “Yes”. This imbalance will affect our prediction and must be addressed when modeling through different techniques.
Then, I explored the categorical features
