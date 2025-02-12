Credit Risk Classification Report

Overview of the Analysis

The purpose of this analysis is to build a machine learning model that can predict loan risk based on borrower financial characteristics. 
We used a logistic regression model to classify loans as either `0` (healthy loan) or `1` (high-risk loan) using historical lending data. 

The dataset includes financial variables such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. 
The goal is to assess whether a borrower is likely to default based on these factors.

Results

Logistic Regression Model Performance

- Accuracy: 99%
- Precision (for high-risk loans, `1`): 89%
- Recall (for high-risk loans, `1`): 92%
- F1-score: 91%

Summary

The logistic regression model performs well, achieving high accuracy (99%) and strong recall (92%) for high-risk loans. This means the model effectively identifies risky loans while keeping false negatives low. 

Given that loan default prediction is a critical task, recall is particularly important—we want to minimize the number of actual high-risk loans classified as healthy. The model performs well in this regard, but there is still a slight tradeoff between precision and recall. 

Recommendation

This model is suitable for use in loan risk assessment** since it captures high-risk loans effectively while maintaining high accuracy overall. However, for an even more precise assessment of high-risk loans, further enhancements such as ensemble learning or cost-sensitive classification methods could be explored.
