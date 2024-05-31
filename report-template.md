# Module 20 Report 

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. 

* Explain the purpose of the analysis. --- The purose of the analysis aimed to assess the effectiveness of a logical regression model in classifying loan applications as either health loans (0) or high-risk loans (1) based on financial attributes.
* Explain what financial information the data was on, and what you needed to predict -- The data consisted of financial information from loan applications includding loan size, interest rate, borrower income, debt to income ratio, number of accounts derrogatory marks and total debt. The target variable was the loan status, categorized as either 0 (healthy loan) or 1 (high-risk loan).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

Machine Learning Process:

* Data Preprocessing: The data was loaded from a CSV file and separated into features (X) and labels (y).
* Train-Test Split: The data was split into training and testing sets using train_test_split to train the model and evaluate its performance on unseen data.
* Model Building: A logistic regression model was created using LogisticRegression from scikit-learn and trained on the training data.
* Model Evaluation: The model's performance was evaluated on the testing data using metrics like accuracy, confusion matrix, and classification report.

Logistic Regression Model:

* Accuracy: 0.9918
* Precision:
- Healthy Loan (0): 1.00
- High-Risk Loan (1): 0.85
* Recall:
- Healthy Loan (0): 0.99
- High-Risk Loan (1): 0.91
* F1-Score:
- Healthy Loan (0): 1.00
- High-Risk Loan (1): 0.88

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. 
- The logistic regression model achieved a high overall accuracy (0.9918) but showed a significant disparity in performance between the two classes. It excelled at predicting healthy loans (precision and recall of 1.00 and 0.99, respectively) but had a lower performance in identifying high-risk loans (precision of 0.85 and recall of 0.91).

- While the overall accuracy seems high, the imbalanced performance between the two classes raises concerns. Because misclassifying a high-risk loan as healthy could lead to financial losses, the current model might not be ideal for real-world applications. It might be beneficial to explore other classification algorithms or techniques to improve high-risk loan prediction without compromising healthy loan identification.
