# credit-risk-classification
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

An overview of the analysis: Explain the purpose of this analysis.
To build a model that can determine creditworthiness of borrowers using a dataset of historical lending activity from a peer-to-peer lending services company. Use historical lending activity to train model.

The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
The balanced accuracy scores and the precision and recall scores of all machine learning models as below that were observed as part of the analysis.

Machine Learning Model 1: Logistics Regression model

The Logistics Regression model performs well according to the balanced accuracy score (99%), precision 0.87 and recall 0.89. however this is due to the data being imbalanced. The number of healthy loans (low-risk) highly outweighs the number of non-healthy (high-risk) loans indicating that the model would predict loan status's as healthy better than being able to predict loan status's as non-healthy. We should run the model with increasing the sample size to increase recall value.


precision    recall  f1-score   support

           0       1.00      1.00      1.00     18759
           1       0.87      0.89      0.88       625

    accuracy                           0.99     19384
   macro avg       0.94      0.94      0.94     19384
weighted avg       0.99      0.99      0.99     19384


