# Overview of the Analysis
This analysis focuses on predicting whether loans are healthy (0) or high-risk (1) based on financial data. The dataset includes variables like loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.

The goal was to build a machine learning model to assess credit risk. Here's the process we followed:

Split the data into training and testing sets.
Trained a logistic regression model to make predictions.
Evaluated the model using precision, recall, and F1-score to measure performance.

## Results
Here’s how the logistic regression model performed:

Healthy Loans (0):
Precision: The model perfectly identified healthy loans without any false positives.
Recall: Almost all actual healthy loans were identified correctly.
High-Risk Loans (1):
Precision: Most of the predicted high-risk loans were correct.
Recall: The model successfully identified nearly all actual high-risk loans.

## Summary
The model is very effective at identifying healthy loans and performs well at catching high-risk loans. 

## Recommendation:
This model is a strong option for credit risk analysis. It is particularly good at identifying high-risk loans, which can be valuable for reducing financial risk. However, if minimizing false positives (misclassifying healthy loans as high-risk) is crucial, additional adjustments may improve performance. Overall, the model is reliable and ready for practical use.
