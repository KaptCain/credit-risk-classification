# credit-risk-classification
module 20 challenge
Overview:
The purpose of this analysis was to predict whether a loan is "healthy" or "high-risk" based on financial data.
Accurate predictions are very important for risk management and informed decision-making in the lending industry.
The financial data included loan size, interest rate, borrower income, debt to income, number of accounts, dergogatory marks, and total amount of debt.
Using this information we predicted whether a loan was healthy or not. 

Model Performance:
Accuracy: 99%

Precision:
        Healthy Loan (0): 1.00
        High-Risk Loan (1): 0.86

Recall:
        Healthy Loan (0): 0.99
        High-Risk Loan (1): 0.94
F1-Score:
        Healthy Loan (0): 1.00
        High-Risk Loan (1): 0.90

Summary:
The Logistic Regression model demonstrates strong overall performance, particularly in predicting healthy loans with near-perfect accuracy. However, its precision and recall for high-risk loans are lower, indicating some misclassification. If minimizing false negatives for high-risk loans is a priority, techniques like oversampling or alternative models (e.g., Random Forest) should be explored. For general risk assessment, the current model is a solid baseline but could be improved for high-risk loan identification.


This code was created by Alec Collins