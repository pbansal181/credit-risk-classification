# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

We have given a historical loan lending data from peer to peer lending services and trying to build a model that can identify the creditworthiness of borrowers which is predicting the risk associated with the loans.


* Explain what financial information the data was on, and what you needed to predict.

The lending data includes loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt and loan status.
Our goal is to predict if the loan is healthy or a high-risk loan using logistic regression model

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

The variable we target to predict is 'loan_status' and the value '0' indicates healthy loans and value '1' shows high-risk loans.

* Describe the stages of the machine learning process you went through as part of this analysis.

For analysis of the data, we follow the below steps:

1. Separate the data into labels and features
2. Split the data into training and testing data by using 'train_test_split'
3. Instantiate a Logistic Regression model
4. Fit the model using training data 
5. Make a prediction using testing data
6. Generate an confusion matrix for the model
7. Print the classification report for the model



## Results

1. Machine Learning - Logistic Regression model
	- The model has 99% accuracy
	- The precision, recall and f1-score is 1 which is ideal.

## Summary

- The logistic regression model demonstrate exceptional performance for '0'(healthy loan) with perfect precision, recall and f1-score which is 1. For '1'(high-risk loans), the model also performs well with 87% precision, 89% recall and 88% f1-score.

- The overall accuracy is 99% which suggests the model performs very well in terms of making correct predictions across both classes. In conclusion, based on this classification report, the logistic regression model is highly effective at predicting both "healthy loans" and "high-risk loans," achieving near-perfect accuracy and demonstrating strong performance metrics for both classes. Hence the model is highly recommended to use by the company.


