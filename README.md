# Credit-Risk-Classification

## Instructions
The instructions for this Challenge are divided into the following subsections:

>Split the Data into Training and Testing Sets
>Create a Logistic Regression Model with the Original Data
>Write a Credit Risk Analysis Report

## Split the Data into Training and Testing Sets
  >Open the starter code notebook and use it to complete the following steps:

  >Read the `lending_data.csv` data from the Resources folder into a Pandas DataFrame.

  >Create the labels set `(y)` from the “loan_status” column, and then create the features `(X)` DataFrame from the remaining columns.

  >Split the data into training and testing datasets by using `train_test_split`.

## Create a Logistic Regression Model with the Original Data
  Use your knowledge of logistic regression to complete the following steps:
  Fit a logistic regression model by using the training data (X_train and y_train).

 Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

Print the classification report.

  >Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
  >

## Write a Credit Risk Analysis Report
Structure your report by using the report template that `Starter_Code.zip` includes, ensuring that it contains the following:

### Credit Risk Analysis Report

1) Explain the purpose of this analysis:

* The purpose of this analysis is to create and evaluate the accuracy of a data model that predicts the credity worthiness of potential borrowers from peer-to-peer lending services
2) Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

* **_Balanced Accuracy Score_**: 95.20%  this means that when taking into account the sensitivity (recall and/or true positive rate) and specificity (true negative rate) of the model, the balanced prediction accuracy was 95.2%
* **_Precision Score_**: 92%  This means 92% of predicted positives were correct
  
* **_Recall Score_**: 95%  this means that the model was 95% precise in measuring true positive values our of all positive predictions made
  
1) Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

I would recommend using this model to predict the creditworthiness of borrowers, because it has over 95% accuracy in predicting the outcome of the repayment of the initial loan. That accuracy range could be easily molded into a business risk profile to ensure sufficient capital flow for the lenders to remain in business/make a profit.

Some codes are sourced  from class activities and  sort assistance from support staff such as TA's.
