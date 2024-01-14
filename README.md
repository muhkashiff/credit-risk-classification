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
  <li>Accuracy</li>
    Balanced Accuracy : 95%<br>
  <li>Precision</li>
    Precision:  Healthy Loan ("0"): 100%<br>
                High risk loand ("1") : 85%<br>
  <li>Recall score</li>
    Recall:  Healthy Loan ("0"): 99%<br>
             High risk loand ("1") : 91% <br>

* Machine Learning Model 2:
 <li>Accuracy</li>
    Balanced Accuracy : 99%<br>
  <li>Precision</li>
    Precision:  Healthy Loan ("0"): 100%<br>
                High risk loan ("1") : 84%<br>
  <li>Recall score</li>
    Recall:  Healthy Loan ("0"): 99%<br>
             High risk loan ("1") : 99% 

## Summary
Original data accuracy increased from 95% to 99% after performing RandomOversampling.
since Original Data was imblananced so accuracy can not be consider  a greater measure of model validation.
However, RandomOverSampling produced better accuracy results.
Recall is also known as True positive rate, this gives a better idea of how many positive values are predicted.
After RandomoverSampling was performed, Recall rate for High Risk Loan ("1") was increased from 91 to 99.
RandomOverSampling model is performing better than Original Data Model.
In my opinion, High Risk Loan prediction is important since it is in best interest of the lender to find the borrower who is not able to pay the money back.
## Reference:
Below link was used only to get clue for RandomOversampling code.
www.github.com/hfattor/credit-risk-classification/tree/main
