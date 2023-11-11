# credit-risk-classification

Module 20 Challenge- Credit Risk Classification

Background In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Instructions

The instructions for this Challenge are divided into the following subsections:

• Split the Data into Training and Testing Sets

• Create a Logistic Regression Model with the Original Data

• Predict a Logistic Regression Model with Resampled Training Data

• Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets

Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

NOTE: A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

Split the data into training and testing datasets by using train_test_split.
Create a Logistic Regression Model with the Original Data

Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

  o	Calculate the accuracy score of the model.

  o	Generate a confusion matrix.

  o	Print the classification report.
Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
Credit Risk Analysis Report

The purpose of this report is to use various techniques to train and evaluate a transgression model to determine the accuracy for healthy and high risk loans.

The lending data consisted of the following: loan size, interest rate, borrower income, debt to income ratio, number of accounts, derrogatory marks, total debt and loan status.

The "target" variable, y, is the loan_status which can be classified as 0 or 1. 0 represents a high risk loan, and 1 represents a high risk loan.

All other data is within the "features" variable, x.

Stages of the Machine Learning Process:

Data Collection and Preparation

Model Selection

Model Training

Model Prediction

Model Utilization

The Logistic Regression Model with the resampling method was used to determine credit risk classification accuracy.

The model's performance was evaluated based on the accuracy score.
