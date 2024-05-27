# credit-risk-classification
Module 20 Challenge

## Python Library Requirements
- pandas
- sklearn

## Report
### Overview
The purpose of this analysis is to use historical lending activity to predict the creditworthiness of borrowers. The target for the analysis is to categorize loans as "healthy" or "high-risk". Features used in the model include:
- loan size
- loan interest rate
- borrower income
- borrower debt-to-income ratio
- borrower number of accounts
- borrower derogatory marks
- borrower debt<br><br>
77,536 records were analyzed with machine learning using a logistic regression model. 75% of the records were used to train the model and 25% of the records were used to test it.

### Results
Logistic regression model accuracy: 0.99
| Target         | Precision | Recall |
|----------------|-----------|--------|
| Healthy Loan   |      1.00 |   0.99 |
| High-Risk Loan |      0.85 |   0.91 |

### Summary
Overall, the model has a high accuracy of 99%. This is reflected by the high precision and recall for healthy loans, which the model can predict reliably. High-risk loans are more difficult for the model to predict. With a precision of 85%, the model will incorrectly predict a loan as high-risk 15% of the time. This may cause the business to reject loans that otherwise would have been profitable. With a recall of 91%, the model will incorrectly predict a high-risk loan as a healthy loan. WiP 
