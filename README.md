Auto Insurance Customer Lifetime Value Prediction
This project focuses on predicting Customer Lifetime Value (CLV) for an auto insurance company using linear regression analysis. The model incorporates various factors such as number of policies, monthly premium, total claim amount, number of open complaints, and marital status to forecast CLV accurately.
Project Overview

Objective: Develop a predictive model for Customer Lifetime Value in the auto insurance sector.
Data Source: UCI ML Repository dataset from Kaggle
Methodology: Linear Regression with log transformations for continuous variables
Key Features: Monthly Premium Auto, Total Claim Amount, Number of Policies, Number of Open Complaints, Marital Status

Key Findings

The model explains approximately 25.56% of the variability in log(CLV).
All predictors are statistically significant (p < 0.05).
Monthly Premium Auto has the strongest positive relationship with CLV.
Number of Open Complaints has a negative impact on CLV.

Model Performance

R-squared: 0.2556
Adjusted R-squared: 0.2552
F-statistic: Significant (p < 2.2e-16)

Challenges and Future Work

Heteroskedasticity issues identified
Potential omitted variable bias
Future improvements could include exploring advanced techniques like XGBoost, Random Forest, and Neural Networks

Skills Demonstrated

Data Analysis and Visualization
Linear Regression Modeling
Statistical Assumption Testing
Business Insight Generation

Tools Used

R (for statistical analysis)
Kaggle (data source)
