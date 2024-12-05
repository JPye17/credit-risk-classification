## Overview of the Analysis

In this Challenge, various techniques were used to train and evaluate a model based on loan risk. Creating a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. The analysis was conducted on financial data, specifically focusing on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The objective was to predict the loan status, either as a healthy loan (0) or unhealthy loan (1).

The stages of the machine learning process in this analysis included:

* Splitting the Data into Training and Testing Sets
* Creating a Logistic Regression Model with the Original Data
* Writing a Credit Risk Analysis Report

## Results

Accuracy: The overall accuracy of the model is 0.99, indicating that it correctly classifies 99% of the instances.

•	Healthy loans (0): The model has a precision of 1.00, Excellent at identifying true positives with very few false positives.
•	Unhealthy loans (1): The model has a precision of 0.87, Moderate effectiveness with more false negatives than desired.
•	Healthy loans (0): The model has a recall of 1.00, Showing this is highly accurate, with few if none false negatives.
•	Unhealthy loans (1): The model has a recall of 0.95, it's effective at identifying high-risk loans with few false negatives.


## Summary

The model is doing a great job at predicting the 0 (healthy loan Status) with perfect scores. There is room for improvement though when predicting the 1 (unhealthy load status) where the precision is lower at .87 but still fairly accurate, the more promising data points to consider are the recall and f1-score being relatively higher. The support is lower, so this does cause a slight pause in how accurate these score may be. A larger data set would be beneficial in analysing the 1 status.
