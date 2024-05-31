# Bank Customer Churn Rate Analysis

## Overview
This project aims to analyze and predict customer churn for a bank by utilizing detailed customer data to track account status (active or closed). High churn rates lead to revenue loss, increased acquisition costs, and reduced profitability. Therefore, proactively managing churn is crucial for sustained growth and competitiveness in the financial industry.

## Dataset
The dataset includes 10,000 rows with the following key features:
- **Credit Score**
- **Geography**
- **Age**
- **Tenure**
- **Balance**
- **Number of Products**
- **Has Credit Card**
- **Is Active Member**
- **Estimated Salary**

Irrelevant features such as row number, customer ID, surname, and gender were removed to prevent bias and enhance model efficiency.

## Data Preparation
1. **Oversampling**: Used SMOTE to balance the target variable distribution.
2. **Label Encoding**: Encoded categorical values into numerical values.
3. **Null Handling**: Filled missing data using mode.
4. **Column Dropping**: Removed unwanted columns to build an efficient model.

## Modeling
Various models were implemented, including:
- Decision Tree
- Logistic Regression
- SVM
- Neural Networks
- Random Forest
- Ensemble Models
- Gradient Boosting
- XGBoost
- K-NN

The standout model was Gradient Boosting with Hyperparameter Tuning, which showed strong performance metrics in precision, recall, and F1-score.

## Model Evaluation
- **Lift/Gain Curve**: By contacting 40% of customers, 85% of those likely to churn can be identified.
- **Feature Importance Analysis**: Identified key factors contributing to churn predictions.

## Deployment Strategies
1. **Batch Processing**: Periodic evaluation of churn risk.
2. **Alerting System**: Notifies stakeholders of high-risk customers.
3. **Feedback Loop**: Continuous monitoring and retraining of the model.
4. **Monitoring Dashboard**: Provides insights into model performance and churn trends.
5. **Interpretability**: Ensures model predictions are understandable to customer-facing staff.

## Future Improvements
- Explore advanced modeling techniques like deep learning.
- Continuous monitoring and iteration to adapt to changing churn patterns.
- Customer segmentation for tailored retention strategies.

This project underscores the importance of leveraging data analytics to manage customer churn effectively, ensuring business sustainability and profitability.
