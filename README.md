# Telco-Churn-Analysis
# Customer Churn Exploratory Data Analysis

## Project Overview

This project explores customer churn patterns using a telecommunications customer dataset obtained from Kaggle. The dataset contains demographic information, account details, subscribed services, billing information, and customer churn status. The goal of this analysis is to identify factors associated with customer retention and customer churn.

Customer churn is an important business metric because retaining existing customers is often more cost-effective than acquiring new ones. Understanding which customers are most likely to leave can help organizations develop targeted retention strategies and improve customer satisfaction.

## Dataset

The dataset includes the following types of information:

* Customer demographics (gender, senior citizen status, partner status, dependents)
* Account information (tenure, contract type, payment method)
* Service subscriptions (internet service, online security, online backup, device protection, tech support, streaming TV, streaming movies)
* Billing information (monthly charges, total charges, paperless billing)
* Customer churn status

## Project Objectives

This analysis seeks to answer the following questions:

1. Do customers subscribed to certain services have higher churn rates than others?
2. Do customers with multiple services churn at a lower rate than customers with only one service?
3. Which customer characteristics are most strongly associated with churn?
4. What overall trends and patterns can be identified within the data?

## Data Preparation

The dataset was cleaned and prepared using Python and Pandas. Key preprocessing steps included:

* Loading the dataset into Google Colab
* Checking for missing values and duplicate records
* Reviewing and correcting data types
* Converting binary variables into numerical format (0 and 1)
* Categorizing variables as binary, categorical, or numerical
* Creating a new feature representing customers with multiple service subscriptions

## Analysis

Exploratory Data Analysis (EDA) was performed to examine customer churn across different customer groups and service subscriptions. Churn rates were calculated by taking the mean of the binary churn variable and converting it to a percentage.

Key areas of analysis included:

* Churn rates by service subscription
* Churn rates for customers with single versus multiple services
* Churn rates by demographic characteristics
* Visualizations highlighting customer retention trends

## Key Findings

* Customers with multiple services had lower churn rates than customers with only one service.
* Gender showed little relationship with churn.
* Senior citizens experienced significantly higher churn rates than non-senior customers.
* Customers with partners and dependents were substantially less likely to churn.
* Several service subscriptions appeared to be associated with improved customer retention.

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Future Improvements

Future work could include developing machine learning models to predict customer churn, evaluating feature importance, and testing strategies for improving customer retention among high-risk customer groups.
