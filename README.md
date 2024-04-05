# credit-risk-classification
 
**Loan Risk Analysis Report**

## Overview of the Analysis

The purpose of this analysis is to employ machine learning models to assess the risk associated with loan applications. By analyzing various factors such as loan size, interest rates, borrower income, and more, we aimed to predict the likelihood of a loan being a risk or not, thereby assisting a financial institution in making informed loan approval decisions. This analysis is crucial for minimizing the risk of default while ensuring healthy loan distribution.

## Dataset

Data Types: loan_size, interest_rate,borrower_income,debt_to_income,num_of_accounts,derogatory_marks,total_debt

**Results**

The performance of the logistic regression model used in this analysis is summarized as follows:

Accuracy Score: 99%
The model correctly predicts loan risk in 99% of cases, indicating its high reliability in overall prediction.
Precision Score:
For low-risk loans: 100%
For high-risk loans: 85%
The model is perfect in identifying low-risk loans but slightly less precise for high-risk loans.
Recall Score:
For low-risk loans: 99%
For high-risk loans: 91%
The model has a high ability to identify the majority of both low and high-risk loans, though it's marginally better at detecting low-risk loans.

## Summary
The logistic regression model demonstrated exceptional performance in identifying low-risk loans with unparalleled precision and substantial accuracy in predicting high-risk loans. Given its high accuracy score, the model proves to be highly effective and reliable in predicting loan risk, making it a valuable tool for financial institutions looking to optimize their loan approval process.

## Recommendation
Given the model's high precision in identifying low-risk loans and still accurate performance in detecting high-risk loans, I recommend this model for use by the company. Its ability to accurately classify the vast majority of loans, coupled with a high recall rate for high-risk loans, ensures that this financial institution can confidently assess loan applications while minimizing the risk of default. 