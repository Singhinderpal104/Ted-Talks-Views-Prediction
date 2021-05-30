# Ted-Talks-Views-Prediction
Project on predicting the views on TED videos.
## Introduction
    In this notebook I've done some simple feature engineering on the TED Talks dataset and I've built machine learning models (Linear Regression, Random Forest and XGBRegressor) and optimised their hyperparameters to predict the number of TED Talks views.
## Workflow
   This project is divided into 3 parts after importing the basic libraires and reading the dataset.
     ### 1. Pre processing:
            **a. EDA**
                 - Checked for null values and duplicates.
                 - Explored all the coulmns to get visualizations.
            **b. Feature Engineering**
                 - Used Target Encoding and One Hot Encoding to encode the categorical variables.
            **c. Data Cleaning**
                 - Treated the outliers.
                 - Imputed the missing values using KNNImputer.
            **d. Feature Selection**
                 - Used f-regression for feature selection.
                 - Dropped the columns with high f-score.
     ### 2. Model Building:
            **a. Fitting different models and tuning hyperparameters**
                 - Tried different models like Linear Regression, Random Forest, XGBoost.
            **b. Comparison of Models**
                 - Compared the performance of all the built models using MAE criteria.
            **c. Final Selection of Model**
                 - Got the best result with Random Forest Regressor model.
     ### 3. Conclusion
## Installation
   The code is written in Python 3.7 using Google Colab Notebook.
