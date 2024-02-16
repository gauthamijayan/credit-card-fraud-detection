# credit-card-fraud-detection

## Dataset of this project is available in :
[Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Raw file is available in :
[raw data](creditcard.csv)


## Problem Statement

A credit card is one of the most used financial products to make online purchases and payments. Though the Credit cards can be a convenient way to manage your finances, they can also be risky. Credit card fraud is the unauthorized use of someone else's credit card or credit card information to make purchases or withdraw cash.


It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. 
The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.


We have to build a classification model to predict whether a transaction is fraudulent or not.

### Contents

#### Data Understanding

#### Exploratory Data Analysis

* Features
* Null values detection
* Missing values detection
* Duplicated values detection
* Get correct Datatype for date
* Visualisation of relationship between different features

  
#### Data Cleaning and Data Preprocessing

* Standardisation of dataset
* Imbalanced Data detection
* Handled Imbalanced data using SMOTE

#### Correlation Analysis
 Correlation matrix

* Train-test split
  
#### Featue Engineering

* Feature extraction
* Feature Engineering

#### Feature Importance

![output_60_0](https://github.com/gauthamijayan/credit-card-fraud-detection/assets/159794319/c9754248-f786-4788-8ce7-ceb1050ba864)


#### Modeling

* Logical Regression Classifier
* Decision Tree Classifier
* Random Forest Classifier
* XG Boost Classifier

  
#### Evaluation

*ROC AUC Score
* ROC Curve
* Confusion Matrix
* Classification report

#### Results on Decision Tree classifier for test data


![output_81_1](https://github.com/gauthamijayan/credit-card-fraud-detection/assets/159794319/1d14b1b0-6de0-41db-a582-524e014f8e41)

![output_82_0](https://github.com/gauthamijayan/credit-card-fraud-detection/assets/159794319/dc5975b1-550f-4ec2-815d-6974298fbfe8)

Model Accuracy is:  0.999365594050682

[[56635    16]

 [   20    75]]
 
              precision    recall  f1-score   support

           0       1.00      1.00      1.00     56651
           1       0.82      0.79      0.81        95
           

    accuracy                           1.00     56746

   macro avg       0.91      0.89      0.90     56746
   
weighted avg       1.00      1.00      1.00     56746

Decision Tree gives an Accuracy of 99.94 % with 100% precision, 100% recall and 100% f1 score.

So it the best model to find frauds in credit cards.

#### Model Serialisation
