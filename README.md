## Credit Risk Analysis

This analysis uses supervised machine learning to predict creditworthiness of borrowers. I use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrower.

* This analysis evaluates loan status as healthy or at risk of default using customer data on loan size, interst rate, debt-to-income ratio, borrower income, and number of cretit accounts with derogatory remarks. 
* First, data is split into training and testing models.
* Two logistic regression models are created and fit with original data and random oversampled data.  
* The trained model is used to make predictions about the data. 
* Performance of the two models is evaluated and compared. 

## Results

* Machine Learning Model 1:
    * Balanced Accuracy was 95%
    * Precision and Recall for predicting healthy loans was 100% and 99% respectively.
    * Precision and Recall for predicting high risk loans was 85% and 91% respectively.

* Machine Learning Model 2:
    * Balanced Accuracy was 99%.
    * Precision and Recall for predicting healthy loans was 100% and 99% respectively.
    * Precision and Recall for predicting high risk loans was 84% and 99% respectively.

## Summary

Analysis shows we can effectively predict healthy lending using supervised machine learning. Randomly oversampling the data helps improve balanced accuracy, and both models were precise in predicting healthy loans. Both models are more precise in predicting healthy loans, but both false positives and false negatives could be costly in the loss of precision in predicting high risk loans. 
