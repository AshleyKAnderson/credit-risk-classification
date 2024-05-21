# Module 12 Report Template

## Overview of the Analysis

In this analysis, the goal was to evaluate the performance of a logistic regression model for predicting the status of loans. The purpose was to determine the model's ability to correctly classify loans into two categories: 0 (healthy loan) and 1 (high-risk loan). This classification is crucial for financial institutions to manage risk effectively and make informed lending decisions.

The financial data used in this analysis included various features relevant to the loans, such as loan amount, interest rate, borrower credit score, and repayment history. The target variable was the loan status, with the goal of predicting whether a loan would be healthy or high-risk.



## Results

Machine Learning Model 1: Logistic Regression

Accuracy: 99%
Precision:
Healthy Loans (0): 100%
High-Risk Loans (1): 85%
Macro Average: 92%
Weighted Average: 99%
Recall:
Healthy Loans (0): 99%
High-Risk Loans (1): 91%
Macro Average: 95%
Weighted Average: 99%


## Summary
The logistic regression model demonstrates high overall accuracy (99%), indicating its strong performance in predicting loan statuses. It excels in predicting healthy loans, with a precision of 100% and recall of 99%. For high-risk loans, the model shows a precision of 85% and recall of 91%. While the model's performance is slightly lower for high-risk loans, it is still quite effective.I recommend using this logistic regression model for the company's loan prediction needs. The model's high accuracy and balanced performance metrics suggest it will be effective in minimizing financial risk while maintaining operational efficiency. However, to address the lower precision for high-risk loans, additional measures such as a secondary validation process or continuous monitoring and retraining of the model should be considered. This approach will ensure that the model remains robust and accurate over time, providing reliable predictions for both healthy and high-risk loans.







