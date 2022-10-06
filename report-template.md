# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis was to determine if a loan was either a healthly loan or a unhealthly loan using customer information.
* The data that we analyzed included information about the loan and the borrower, such as loan size, the interest rate, income, debt to income ratio, number of accounts they have, and any derogitory marks. The healthly loans were labeled at '0' and unhealthy loans as '1'. 
* The 0 labeled loans numbered 75036 while the 1 labeled numbered 2500. 
* We split the customer data into variable X and the binary loan status into variable y 
* We then preformed a test_train_split of the data in order to do our linear regression alaysis using sklearn. 
* Once we fitted our model and using the predict function we created a classification model of the results. 
* We also proformed an oversampling of the data in order to gain a clearer understanding of our analysis results.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * Accuracy 0.9520479254722232 
  * Precision 
    * 0 1.00 
    * 1 0.85 
  * Recall 
    * 0 0.99 
    * 1 0.91 

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Accuracy 0.9936781215845847 
  * Precision 
    * 0 0.99 
    * 1 0.99 
  * Recall 
    * 0 1.00 
    * 1 0.84

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any.

* The oversampled data model was a little less accurate in terms of the balanced accuracy score, however it seems to have a slightly level of accuracy due to a lower spread between the precision and recall values of both the 0 and 1 labels.

* While it is imporatnt to identify both classes correctly. Since Unhealthy Loans can cause our company more in loses it is important to identify them correctly at a higher rate.
