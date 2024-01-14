# credit-risk-classification Report
## Overview of the Analysis

Purpose of the analysis is to build a model to determine the creditworthiness of borrowers.
The data contains borrowing status and income of the borrower.Loan status is predicted Vs the actual status to validate the model.
value_count() is used to determine the values of ("0") and ("1").
Logistic Regression was performed based on Original data then using RandomOverSampling.
Data was went through process of splitting, fitting and predicting.
these parameters were used to generate metrics results for evaluation of model.

## Results
Belowe are results of Logistic Regression Models. 
<ul>Machine Learning Model 1- Original data</ul>
<ul>Machine Learning Model 2- RandomOverSampling</ul>

* Machine Learning Model 1:
  <ul>Accuracy</ul>
    Balanced Accuracy : 95%
  <ul>Precision</ul>
    Precision:  Healthy Loan ("0"): 100%
                High risk loand ("1") : 85%
  <ul>Recall score</ul>
    Recall:  Healthy Loan ("0"): 99%
             High risk loand ("1") : 91% 

* Machine Learning Model 2:
 <ul>Accuracy</ul>
  <ul>Precision</ul>
  <ul>Recall score</ul>

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
