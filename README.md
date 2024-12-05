## Overview of the Analysis

In this Challenge, various techniques were used to train and evaluate a model based on loan risk. Creating a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. The analysis was conducted on financial data, specifically focusing on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The objective was to predict the loan status, either as a healthy loan (0) or high-risk loan (1).

The stages of the machine learning process in this analysis included:

* Splitting the Data into Training and Testing Sets
* Creating a Logistic Regression Model with the Original Data
* Writing a Credit Risk Analysis Report

## Results

Accuracy: The overall accuracy of the model is 0.99, indicating that it correctly classifies 99% of the instances. Precision:

* Healthy loans (0): The model has a precision of 1.00, which means it's excellent at identifying true positives with very few false positives.
* High-risk loans (1): The model has a precision of 0.87, indicating its moderate effectiveness in identifying high-risk loans with some false positives. Recall:
* Healthy loans (0): The model has a recall of 1.00, which means it's correctly identifying nearly all instances of healthy loans with very few false negatives.
* High-risk loans (1): The model has a recall of 0.89, indicating its effectiveness in identifying high-risk loans with some false negatives.

## Summary

Based on the results, the logistic regression model trained with resampled data (Model 2) performs better than the model trained with original data (Model 1), particularly in predicting high-risk loans. Model 2 demonstrates higher precision and recall scores for high-risk loans, which is crucial in minimizing potential financial losses for the lending company.

I recommend using the logistic regression model trained with resampled data (Model 2) for credit risk analysis, as it shows a significant improvement in predicting high-risk loans compared to the original model. This model will help the company effectively assess loan applications and make informed decisions when approving or rejecting loans, thus mitigating credit risk.
