Telecom Customer Churn – Analysis and Predictive Modelling

Project Overview

This project presents both exploratory data analysis (EDA) and machine learning modelling on a telecom customer dataset to understand and predict customer churn. The analysis identifies key factors influencing churn, while the predictive model helps detect customers at risk of leaving.

Objective

The objective of this project is to:

• Explore customer demographics, service usage, and billing behaviour

• Identify patterns associated with customer churn

• Build a machine learning model to predict churn

• Evaluate model performance using appropriate metrics

• Provide actionable insights to support customer retention strategies

Dataset

• Number of observations: 7,043 customers

• Target variable: Churn (Yes / No)

Key feature groups include:

• Demographics: gender, senior citizen status, partner, dependents

• Services: internet service, streaming services, online security, technical support

• Contracts and billing: contract type, payment method, tenure, monthly and total charges

Tools and Libraries

Python · pandas · numpy · matplotlib · seaborn · scikit-learn

Analysis Workflow

Data Loading and Inspection

The dataset was loaded and examined to understand its structure, variables, and data types.

Data Quality Checks

No duplicate records or missing values were found. The dataset was clean and suitable for analysis.

Exploratory Data Analysis

Univariate and bivariate analysis were conducted to understand distributions and relationships between variables. Visualisations were used to identify churn patterns.

Feature Engineering and Preprocessing

Categorical variables were encoded, and numerical features were prepared for modelling.

Model Development

A Random Forest classifier was used to predict customer churn. The dataset was split into training and testing sets using stratified sampling.

Model Evaluation

The model was evaluated using accuracy, precision, recall, F1-score, and ROC-AUC. Threshold tuning was applied to improve churn detection.

Key Insights

• Customers with shorter tenure are more likely to churn

• Month-to-month contracts show significantly higher churn

• Higher monthly charges are associated with increased churn risk

• Fiber optic users exhibit higher churn compared to other services

• Customer engagement and service features influence retention

Model Performance

• Accuracy: ~80%

• ROC-AUC: ~0.83

• Improved recall for churn prediction after threshold tuning

Conclusion

This project demonstrates how both data analysis and machine learning can be used to understand and predict customer churn. The results highlight key risk factors and provide a foundation for targeted retention strategies. The predictive model can support proactive decision-making by identifying customers who are most likely to leave.

