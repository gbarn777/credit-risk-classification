# Module 12 Report Template

## Overview of the Analysis

The overall purpose of this analysis is to build a model capable of accurately identifying theh creditworthiness of borrowers using a dataset of historical lending activity. The dependent variable was "loan status", as that is what is used to determine and classify the creditworthiness of an individual. The independent variables used were laon size, interest reate, borrower income, debt to income ratio, number of accounts, and derogatory marks. These are all variables typically used by lenders to assign classifications to borrowers and can often impact how likely they are to be approved for loans, and how large those loans may be. 

In order to accomplish this, the data was split into training and test sets. Variables were defiined in order to create two different regression models using the original data set and a randomly oversampled data set. The performance of both were then compared. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
-Predicted healthy loans 100% of the time. 
-Predicted non-healthy loans around 85% of the time. 
-The model made 1% of misatkes when predicting healthy loans and 9% of mistakes when predicting non-healthy loans. 



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
-Predicted healthy loans 100% of the time. 
-Predicted non-healthy loans around 84% of the time. 
-The model made 1% of mistakes when predicting healthy loans and 9% of mistakes when predicting non-healthy loans. This is due to the dataset being BALANCED. 

## Summary

The Logistic Regression model fitted with oversampled data performed much better than the model fitted with imbalanced data due to the data being balanced and generating a higher accuracy score and a higher recall, indicating that the model will make extremely fewer mistakes when classifying non-healthy loans. Due to the nature of the project, the lending company would most likely want fewer false positives due to the high possibility of a lender loosing provided funds when classifying non-healthy loans as healthy. Because of this, I would recommend usng Model 2 (Logistic Model) fitted with oversampled data. 
