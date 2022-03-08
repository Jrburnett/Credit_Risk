# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis. 

The purpose of this analysis is to determine wether a loan is risk or healthy, in order to identify the credit worthiness of the borrowers.
* Explain what financial information the data was on, and what you needed to predict.

The financial data that was used was for the prediction is loan size, interest rate, income of the applicant, debt to income, number of accounts, total debt and loan status. The goal of the project is to predict wether the institution should give the loan out or decline the loan due to risk of the applicant
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

The variable I am trying to predict is the loan status. In predicting the loan status I use the other data on the user applying in order to predict if the loan would be given to the applicant.
* Describe the stages of the machine learning process you went through as part of this analysis.

The machine learning process I went through was splitting and training the orginal data, I then ran a logistic regression model which measures the possibility of passing or failing the loan status variable. I then fit the logistic regression model and then predicted the logistic regression model. After going through the process for the orginal data, I then went through the same process for the resampled data. 
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

Logistic regression model was a key part of this assignment, logistic regression model is used to predict the outcome of a class with an outcome of pass/fail, or for my assignment, loan granted or loan denied. I also used random oversampling which invovles which invovles selecting examples for a smaller class, replacing them and adding them to the orginal dataset. 
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

The balance accuracy score of the first model is 95%

The average precision of the first model is 99%, predicting 100% precision for approval of the loan and 85% precision for denial of the loan

The average recall scores for the first machine learning model is 99%, 99% recall for approval of the loan and 91% recall for denial of the loan

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

The balance accuracy score of the second model is 99%

The average precision of the second model is 99%, predicting 100% precision for approval of the loan and 84% precision for denial of the loan

The average recall scores for the second machine learning model is 99%, 99% recall for approval of the loan and 99% recall for denial of the loan
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?

Both of the machine learning models perform well. The first machine learning model however does perform better than the second, and this is because it has a higher precision of denial of the loan for unhealthy applicants, while also maintaining a high accuracy score, as well as precision for healthly loans and recall scores for both. 
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

Performace does depend on the problem we are trying to solve. In this assignment we are attempting to find as many unhealthly applicants and deny them the loan, while also maintaining a high precision and accuracy for healthly loans. Each individual performance depends on the problem at hand.

If you do not recommend any of the models, please justify your reasoning.
