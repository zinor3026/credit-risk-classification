# Credit Risk Classification Report 

## Overview of the Analysis

* In this analysis, I want to train and evaluate a model based on loan risk
* I want to build a model that can identify the creditworthiness of borrowers using a dataset of historical lending activity from a peer-to-peer lending services company.
* Here, we are trying to predict whether the borrower is a healthy loan or a high-risk loan.
* Throught out this process, I have done the loaded, preprocess, and split the data to be ready for logistic regression model.
* In this analysis, I used Logistic Regression model and also used over sampling method with Logistic regression. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Logistic Regression Model 1:
  * This model has an overall accuracy of 0.99. It performs very well to determine the healthy loans i.e 1 and has 0.87 points in recognising the high-risk loan. This model can be more useful in finding a healthy loan. 



* Logistic Regression with a resampled data:
  * This model has an overall accuracy of 1. It performs very well to determine the healthy loans and has 0.87 points in recognising the high-risk loan. 

## Summary

* The Logistic Regression model fitted on the oversampler data has a better accuracy than the logistic regression without the oversampler data. The precision was same but the recall is also better for the Logistic Regression model fitted on the oversampler data.
* In this scenario, it will be more beneficial if we can predict the high-risk loans as it can help us make a better decision as to whether we should loan the money to this borrower or not. 

