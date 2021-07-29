# Capstone Project: Acquisition ScoreCard for Banks

This problem is about loan defaulters prediction. For this, I have used dataset provided by College.

The dataset contains 35 features such as Age, Net Income, Customer Type, Industry, Organization, Total Enquires in last 12 months, Unsecured amount, Total no. of loans(Live + Closed), Debt Ratio etc. I have developed a machine learning model to predict loan defaulters.

**This ML model is able to predict 92% of the defaulters.**

1. Exploratory Data Analysis and Data Cleaning:
   - Done following cleaning operations:
      * Null value imputation
      * Creating dummy variables
      * Handling outliers
      * Selecting relevant features
         - For Feature Selection we have used:
           * Random Forest
           * Information Value
           * Varclus
           * Lasso Regression

2. Training a machine learning model:
   - Included in 'Acq_Scorecard.ipynb'
   - Models used:
      * Forward Logistic Regression
      * Backward Logistic Regression
