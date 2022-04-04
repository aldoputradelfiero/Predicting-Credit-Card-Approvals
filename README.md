# PredictingCredit Card Approvals
Project Predicting Credit Card Approvals

- Topic : Machine Learning
- Programming languages : R
- Packages : dplyr, ggplot2
- Algorithms used :


## Introduction  : 
Commercial banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. In this project, we had built an automatic credit card approval predictor using machine learning techniques, just like the real banks do.

# Data :
The dataset used in this project is the Credit Card Approval dataset from the UCI Machine Learning Repository.

# Approach :
- First, we will start off by loading and viewing the dataset.
- We will see that the dataset has a mixture of both numerical and non-numerical features, that it contains values from different ranges, plus that it contains a number of missing entries.
- We will have to preprocess the dataset to ensure the machine learning model we choose can make good predictions.
- After our data is in good shape, we will do some exploratory data analysis to build our intuitions.
- Finally, we will build a machine learning model that can predict if an individual's application for a credit card will be accepted.
 
## Summary :
While building this credit card predictor, we tackled some of the most widely-known preprocessing steps such as scaling, label encoding, and missing value imputation. We finished with some machine learning to predict if a person's application for a credit card would get approved or not given some information about that person. We have achieved 86% of accuracy. 86% is the best we could get from this data using both the model logistic regression.
