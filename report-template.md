# Module 12 Report Template

## Overview of the Analysis

The objective of this analysis is to utilize logistic regression for the purpose of distinguishing between reliable clients and those who might pose a substantial risk of defaulting on their potential financial obligations. The variables considered for this analysis encompass factors such as loan amount, interest rate, income, debt-to-income ratio, the number of accounts, derogatory marks, and total debt.

To ensure the influence of this data on lending decisions, we will establish two categories. Class 0 will represent clients considered "creditworthy", while Class 1 will be designated for clients categorized as having "high credit risk".

The techniques employed in this analysis consist of Logistic Regression for model fitting and prediction, along with the implementation of RandomOverSampler to balance the dataset for model fitting and prediction.
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  
### Healthy Loans 

- **Precision:** 100%
- **Recall:** 99%
- **F1-Score:** 1.00

The model exhibits outstanding performance in predicting healthy loans, with a perfect precision score, indicating that it correctly identifies healthy loans all the time. Additionally, it has a high recall score, suggesting it can capture nearly all of the healthy loans in the dataset.


* Machine Learning Model 2:
### High-Risk Loans 

- **Precision:** 84%
- **Recall:** 99%
- **F1-Score:** 0.91

For high-risk loans, the model maintains a good level of precision, correctly identifying high-risk loans 84% of the time. It also demonstrates excellent recall, indicating its ability to capture nearly all high-risk loans.
## Summary

The logistic regression model trained on oversampled data performs exceptionally well in predicting both healthy and high-risk loans. It achieves high precision, recall, and F1-scores for both loan categories, making it a reliable tool for loan classification tasks.

For further details on the model's implementation and usage, please refer to the code and documentation provided in this repository.

Feel free to use and adapt this model for your own loan classification projects. If you have any questions or need assistance, please don't hesitate to reach out.


