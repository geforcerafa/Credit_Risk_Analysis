# Supervised Machine Learning and Credit Risk


Supervised Machine Learning using Python, scikit learn, and imbalanced learn.

## Overview of Project

In this project we are conducting supervised machine learning, to analyze the performance of different algorithms to detect high risk loans. This type of analysis is done in an asymmetric dataset, the vast majority are low risk loans, but it is very important to have a high precision in finding the high-risk loans. In this kind of analysis, a particularly useful metric is the Balance Accuracy Score.

To measure the performance of each algorithm we are going to calculate and compare the Balanced Accuracy Score, the Precision as well as the Recall or Sensitivity. 



### Resources used:
-	Data Sources: LoanStats_2019Q1.cs
-	Software: Python, scikit learn, and imbalanced learn.


## Results:

Here is a summary of the results found.

### Balance Random Forest Classifier

After applying the Balance Random Forest Classifier, we got the following results:

•	Balanced Accuracy Score: 78.8%

•	Precision: 
o	High risk: 4%
o	Low risk: 100%

•	Recall:
o	High risk: 67%
o	Low risk: 91%

### Easy Ensemble AdaBoost Classifier

After applying the Easy Ensemble AdaBoost Classifier, we got the following results:

•	Balanced Accuracy Score: 92.6%

•	Precision: 
o	High risk: 7%
o	Low risk: 100%

•	Recall:
o	High risk: 91%
o	Low risk:94%

### Oversampling

After applying Oversampling, we got the following results:

•	Balanced Accuracy Score: 64.1%

•	Precision: 
o	High risk: 1%
o	Low risk: 100%

•	Recall:
o	High risk: 60%
o	Low risk: 68%

### SMOTE Oversampling

After applying SMOTE Oversampling, we got the following results:

•	Balanced Accuracy Score: 63.7%

•	Precision: 
o	High risk: 1%
o	Low risk: 100%

•	Recall:
o	High risk: 60%
o	Low risk: 68%

### Undersampling

After applying Undersampling, we got the following results:

•	Balanced Accuracy Score: 51.6%

•	Precision: 
o	High risk: 1%
o	Low risk: 100%

•	Recall:
o	High risk: 60%
o	Low risk: 43%

### Combination (Over and Under) Sampling

After applying the Combination (Over and Under) Sampling, we got the following results:

•	Balanced Accuracy Score: 62.4%

•	Precision: 
o	High risk: 1%
o	Low risk: 100%

•	Recall:
o	High risk: 70%
o	Low risk: 55%

## Summary

From the techniques analyzed the one that had better results was the Easy Ensemble AdaBoost Classifier. 

Balance Accuracy Score 92.6%



![Easy Ensamble AdaBoost Classifier Confusion Matrix ](https://user-images.githubusercontent.com/96758511/168874555-853e2ba4-2ea4-45d8-9063-d90d9e1dccc6.png)


Confusion matrix of the Easy Ensemble AdaBoost Classifier



![Easy Ensamble AdaBoost Classifier Imbalanced Classification Report](https://user-images.githubusercontent.com/96758511/168874607-42c31fca-30cc-44c6-a69f-e67482b5ec8d.png)


Imbalanced classification report of the Easy Ensemble AdaBoost Classifier


The only low measure it had was the high-risk precision of 7%. Meaning that it had many false positives. Other than that, the balanced accuracy score was the highest of the six with 92.6%. The recall for the high risk was 91%, low risk 94%. And the precision for the low-risk loans was of 100% 
