# Credit Risk Prediction Model

### Background 
The task was to train and evaluate a model based on loan risk using a historical lending dataset. This model will be used to indentify the creditworthiness of borrowers. Credit risk assessment is crucial for financial institutions as it helps in determining the likelihood that a borrower may default on a loan. By accurately predicting the credit risk, companies can make informed decisions on whether to approve loans, which minimizes potential losses and maintaining financial stability. 

The information in this model uses the below types of financial information to predict the loan risk:
- Loan Size
- Interest Rate
- Borrower Income
- Debt to Income
- Number of Credit Accounts
- Derogatory Marks
- Total Debt

## Analysis Overview 

Below are the steps that I took to build this model:
- Spilt the data into training and testing sets
  - Read the exel file data into a dataframe
  - Created the labels set (y) from the "loan_status" column
  - Created the features (x) DataFrame from the remaining columns, and splitting the data into training and testing datasets by using "train_test_spilt".
- Create a logistic regression model with the original data.
  - Fit the logistic regression model by using the training data (X_train) and (y_train)
  - Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model
  - Evaluated the performance by generating a confusion matrix and a classification report.

## Results 
The machine learning model demonstrated strong performance with the following scores:
- <b> Accuracy </b>: 92%
- <b> Precision </b>: 95%
- <b> Recall </b>: 95%


## Conclusion 
The scores indicate that the model is highly accurate in its predictions, with the stronger scores being between Precision and Recall. It successfully identifies a high number of actual positive cases (credit risk) while maintaing a low rate of false positives. This model's ability to generalize from the training data to unseen data suggests that it can be a reliable tool for assessing credit risk for borrowers. 
