## Overview of the Analysis

The purpose of this analysis is to evaluate the performance of two logistic regression machine learning models in predicting the credit risk associated with loans. The analysis was conducted on financial data, specifically focusing on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The objective was to predict the loan status, either as a healthy loan (0) or high-risk loan (1).

The stages of the machine learning process in this analysis included:

* Splitting the data into training and testing datasets
* Creating and fitting a logistic regression model with the original data
* Evaluating the model's performance using accuracy, precision, and recall scores
* Resampling the data using RandomOverSampler to address class imbalance
* Creating and fitting another logistic regression model with the resampled data
* Evaluating the performance of the resampled model using the same metrics
* 
Methods used in this analysis include LogisticRegression and RandomOverSampler for resampling.

## Results

Accuracy: The overall accuracy of the model is 0.99, indicating that it correctly classifies 99% of the instances. Precision:

* Healthy loans (0): The model has a precision of 1.00, which means it's excellent at identifying true positives with very few false positives.
* High-risk loans (1): The model has a precision of 0.87, indicating its moderate effectiveness in identifying high-risk loans with some false positives. Recall:
* Healthy loans (0): The model has a recall of 1.00, which means it's correctly identifying nearly all instances of healthy loans with very few false negatives.
* High-risk loans (1): The model has a recall of 0.89, indicating its effectiveness in identifying high-risk loans with some false negatives.

## Summary

Based on the results, the logistic regression model trained with resampled data (Model 2) performs better than the model trained with original data (Model 1), particularly in predicting high-risk loans. Model 2 demonstrates higher precision and recall scores for high-risk loans, which is crucial in minimizing potential financial losses for the lending company.

I recommend using the logistic regression model trained with resampled data (Model 2) for credit risk analysis, as it shows a significant improvement in predicting high-risk loans compared to the original model. This model will help the company effectively assess loan applications and make informed decisions when approving or rejecting loans, thus mitigating credit risk.