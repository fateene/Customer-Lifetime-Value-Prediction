# Customer-Lifetime-Value-Prediction
# Overview

  This project focuses on predicting Customer Lifetime Value (CLV) using machine learning models. The goal is to identify high-value customers and optimize marketing strategies.

# Data
  The dataset includes transactional and behavioral customer data. Temporal variables were transformed into durations for better interpretability.

# Models
XGBoostClassifier: Used to classify customers into high and low LTV groups.
XGBoostRegressor: Applied for precise CLV prediction, leveraging the Tweedie distribution.

# Preprocessing
Handling missing values
Feature engineering (e.g., converting dates into meaningful durations)
Scaling and encoding categorical variables


# Results
The models effectively distinguish between high and low-value customers, enabling better decision-making for customer retention and acquisition.


# Technologies Used
Python (Pandas, NumPy, Scikit-learn, XGBoost)
Data visualization (Matplotlib, Seaborn)


# Next Steps
Further feature engineering
Hyperparameter tuning
Deployment of the model for real-time predictions
