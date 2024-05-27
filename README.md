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
The logistic regression model has a high accuracy of 99%. This is reflected by the high precision and recall for healthy loans, which the model can predict reliably. High-risk loans are more difficult for the model to predict. With a precision of 85%, 15% of the loans predicted as high risk are actually healthy. This may cause the business to reject loans that otherwise could have been profitable. With a recall of 91%, the model will incorrectly predict 9% of high-risk loans as healthy loans. This may cause the business to take on unaccounted for risk. <br><br>
This model is good at distinguishing between healthy and high-risk loans. However, whether the company uses the model should be guided by a comparison with a baseline. If this model has greater accuracy, precision, and recall than what is currently in use, then the company should implement this new model. In the case where this model has lesser accuracy, precision, and/or recall than what is currently in use, the losses must be weighed against any savings associated with using the model.
