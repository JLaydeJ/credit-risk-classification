# Instructions
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

## Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
3. Split the data into training and testing datasets by using train_test_split.

## Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

1. Fit a logistic regression model by using the training data (X_train and y_train).

2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

3. Evaluate the model’s performance by doing the following:

  - Generate a confusion matrix.

  - Print the classification report.

4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

## Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

1. An overview of the analysis: Explain the purpose of this analysis.

  - The purpose of this analysis is to predict whether or not a loan is healthy (low risk) or high-risk. The analysis is based on an individual's loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The logistic regression categorizes between the two types of loans, 1 - which is high-risk loans, and 0 - which is healthy loans. We have taken target(y) as loan_status and every other column as feature(X). Once that was completed we used train-test-split and then used the logistic regression on the original data and created the confusion matrix. Finally we printed the classification report for the model.

2. The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

4. A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.
