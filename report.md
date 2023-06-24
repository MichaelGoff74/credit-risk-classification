## Overview of the Analysis

The purpose of this analysis was to break down the data and evaluate the accuracy of a supervised data model that helped predict the creditworthiness of potential borrowers for a peer to peer lending services company.

The dataset that we used for this challenge was the historical lending activity from our peer to peer lending services company.

The basic information we were trying to use to predict the value_counts was from the loan_status column. Basically finding out if the loan was a healthy loan or if it was a high risk loan.

We basically separted the loan_status column from the rest of the data and then broke it down into a train / test / split method with the other data. Using that we fit it into a Logical Regression Model. 

As stated above, we used a Logical Regression Model to form our data and build our models performace using a confusion matrix.

## Overview of the Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Logical Regression Model using Original Data:
    - The Balance Accuracy Score was 94.43%
    - Precision Score was 94%
    - Recall Score was 94%

* Logical Regression Model using Revised with RandomOverSampler Data:
    - The Balance Accuracy Score was 99.42%
    - Precision Score was 99%
    - Recall Score was 99%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

Looking at the performance of both of our models using the original data and the revised data, we had Balance Accuracy Scores of 94.43% and 99.42%, that tells me that either model used to predict the viable loan canidate could be used. The one with the revised data did provide a much more accurate assessment of the data.

We could use this model to predict the creditworthiness of our current clients based on past performance because we achieved such an high Balance Accuracy Score in predicting the loan repayment outcome. It solves our problem in trying to predict if we should issue higher risk loans or not. 
