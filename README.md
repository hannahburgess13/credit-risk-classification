# credit-risk-classification

## Overview of the Analysis

In this Challenge, I used various techniques to train and evaluate a model based on loan risk. A dataset was used from historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers for healthy and high risk loans. 

- to start, the data was split into training and testing sets.
  - ths included changing lending_data.csv into a pandas dataframe, and then spliting the "loan_status" colum from the remaining columns.
- a logistic regression model was then created
  - predictions were made from the training data, and then tested the model's performance by creating a confusion matrix.

## Results

* Machine Learning Model 1:
  * The logistic regression model does a good job of prediciting healthy and high risk loans. From the chart, we can see that the model was able to predict a healthy loan with 100% precision, and 85% precision for high risk loans. We can also see that overall, this model has 99% accuracy when prediciting such factors.  



* Machine Learning Model 2:
  * The logistic regression model works well with this oversampled data, as the results yeild a balance accuracy score of 0.99, showing a 99% accuracy for both healthy and high risk loans, as well as 99% precision.

    
## Summary

Overall, both models did very well in predicting a healthy or high risk loan. However, through the results, machine learning model 2 had a higher probability of accurately and precisely predicitng the outcome. This being said, model 1 had an 85% precision for high risk loans, which is useful and could yield mostly correct results. Both models can predict seemingly accurate results, but I would most likely recomment model 2 for its higher accuracy rate. 
