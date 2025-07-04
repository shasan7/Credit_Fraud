# Detecting Fraud Transactions using the Credit Card Fraud Detection dataset

## Dataset Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Kaggle Notebook: https://www.kaggle.com/code/shasan7/credit-fraud

Used scikit-learn's machine learning models for prediction. Logistic Regression, Random Forest, Support Vector Machine, XGBoost, Ridge Classifier and SGD Classifiers were run.

**The Random Forest, Support Vector Machie and XGBoost classifiers all got nearly 100% accuracy**, but the **XGBoost** has a macro average **F1-Score of 0.93**, while **Random Forest got 0.92 and SVM got 0.79** as F1-Score. 
XGBoost was trained with **100 estimators** using the **"logloss" evaluation metric**, and **"balanced" value was passed to the class_weights** parameter to **provide attention to the minority class, which is crucial for a dataset like ours with huge class imbalance**.

Obtained the following results:

Classifiers:  LogisticRegression has a score of 98.0 % accuracy score.

    Classification Report: 

               precision    recall  f1-score   support

           0       1.00      0.98      0.99     56864
           1       0.06      0.92      0.11        98

    accuracy                           0.98     56962
    macro avg      0.53      0.95      0.55     56962
    weighted avg   1.00      0.98      0.99     56962

    Confusion Matrix: 
     [[55478  1386]
     [    8    90]] 


Classifiers:  RandomForestClassifier has a score of 100.0 % accuracy score.

    Classification Report: 

               precision    recall  f1-score   support

           0       1.00      1.00      1.00     56864
           1       0.96      0.74      0.84        98

    accuracy                           1.00     56962
    macro avg      0.98      0.87      0.92     56962
    weighted avg   1.00      1.00      1.00     56962

    Confusion Matrix: 
     [[56861     3]
     [   25    73]] 


Classifiers:  RidgeClassifier has a score of 99.0 % accuracy score.

    Classification Report: 

               precision    recall  f1-score   support

           0       1.00      0.99      0.99     56864
           1       0.10      0.85      0.17        98

    accuracy                           0.99     56962
    macro avg      0.55      0.92      0.58     56962
    weighted avg   1.00      0.99      0.99     56962

    Confusion Matrix: 
     [[56076   788]
     [   15    83]] 


Classifiers:  SGDClassifier has a score of 93.0 % accuracy score.

    Classification Report: 

               precision    recall  f1-score   support

           0       1.00      0.93      0.96     56864
           1       0.02      0.93      0.04        98

    accuracy                           0.93     56962
    macro avg      0.51      0.93      0.50     56962
    weighted avg   1.00      0.93      0.96     56962

    Confusion Matrix: 
     [[53003  3861]
     [    7    91]] 


Classifiers:  SVC has a score of 100.0 % accuracy score.

    Classification Report: 

               precision    recall  f1-score   support

           0       1.00      1.00      1.00     56864
           1       0.48      0.76      0.58        98

    accuracy                           1.00     56962
    macro avg      0.74      0.88      0.79     56962
    weighted avg   1.00      1.00      1.00     56962

    Confusion Matrix: 
     [[56783    81]
     [   24    74]] 


Classifiers:  XGBClassifier has a score of 100.0 % accuracy score.

    Classification Report: 

               precision    recall  f1-score   support

           0       1.00      1.00      1.00     56864
           1       0.91      0.81      0.85        98

    accuracy                           1.00     56962
    macro avg      0.95      0.90      0.93     56962
    weighted avg   1.00      1.00      1.00     56962

    Confusion Matrix: 
     [[56856     8]
     [   19    79]] 
