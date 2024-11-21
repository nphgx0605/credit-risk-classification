# Module 12 Report Template

## Overview of the Analysis
The purpose of this analysis is to evaluate and define the Healthy loans [label 0] and High-risk loans [Label 1] based on historical lending data. 
The data provided contain the information such as: loan size,interest rate,borrower income,debt to income,num of accounts,derogatory marks,total debt,loan status
Based on these information, we can use Machine Learning to predict and divide the borrowers to 2 identified groups abocve

## Results
Logistic Regression Model
Accuracy: 99%
Precision for Healthy Loans (Label 0): 100%
Recall for Healthy Loans (Label 0): 99%
Precision for High-Risk Loans (Label 1): 85%
Recall for High-Risk Loans (Label 1): 91%
Macro Average F1-Score: 0.94
Weighted Average F1-Score: 0.99

## Summary
The logistic regression model performs exceptionally well, particularly for healthy loans (label 0). It achieves perfect precision and near-perfect recall for identifying healthy loans, ensuring very low false positives. While the precision for high-risk loans (label 1) is slightly lower, the recall of 91% ensures most high-risk loans are correctly identified.

