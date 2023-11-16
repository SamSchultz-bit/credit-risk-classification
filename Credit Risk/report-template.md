# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of the analysis is to identify the credit-worthiness of borrowers.
* Explain what financial information the data was on, and what you needed to predict.
I used information  from people's borrowing history, loan size, interest rate, income, debt to income ratio, number of accounts, and derrogatory marks to predict wether the were marked healthy or high risk.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
loan_size = value of the loan
interest_rate = rate of interest for the loan
borrower_income = annual income for the borrower
debt_to_income = total debt compared to annual income
num_of accounts = number of open accounts 
derrogatory_marks = eg. late payments or defaults
* Describe the stages of the machine learning process you went through as part of this analysis.
Split the data set, fit a logistic regression model to the training data
save the predictions for the testing data labels, evaluate the model's performance
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
      * Precision: healthy = 100%, high risk = 85% 
      * Recall: healthy = 99%, high-risk = 91%
      * Accuracy: 99%



## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

The model predicts the healthy loans at 100% and the righ-risk loans at 88%. Taken with the weighted avg of 99%, the model does a great job with predicting credit-worthiness, and I recoomend it for use.

