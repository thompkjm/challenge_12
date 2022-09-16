# Challenge 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* We performed 2 analyses. One with the original data to train a linear regression model to predict whether a credit loan was health or of high risk based on a number of factors - Loan size, Interest rate, Borrower income, Debt to income (DTI), Number of accounts, Derogatory marks, and Total debt
* We then compared those results with the results by randomly oversampling high risk loans to see if that model can better predict high risk loans since those are what matter to identify more as a lender
* We used basic model machine learning process of creating model, fitting the model, then predicting, then comparing results for accuracy

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1: Original Data Model
  * This model was 95.2+% accurate. Was very precise with 100% precision predicting health loans, and 85% precise predicting high risk loans. Further, this model had 99% recall on health loans, while 91% recall predicting high risk loans. Overall, a better model to predict



* Machine Learning Model 2: Oversampled High Risk Loan Model
  * This model was 99.3+% accurate. Was very precise with 100% precision predicting health loans, and 84% precise predicting high risk loans. Further, this model had 99% recall on health loans, while 99% recall predicting high risk loans. Overall, a better model to predict

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* The model that oversamples the high risk loans performs better for the purpose of the model. As a lender, we are more concerned with identifying loans at risk of default rather than just healthy loans vs performing loans. Thus the higher recall is more important as it identifies the percent of high risk loans. 
* Thus the performance of these models does depend alot on the problem. If our entire goal was to maximize the number of loans, and thus any loan it predicts to be high risk is certainly high risk then precision would be more important. And one could argue the original data model could be better.
* However, our goal as a lender is to identify as many high risk loans as possible, the oversampled model is the better model.
