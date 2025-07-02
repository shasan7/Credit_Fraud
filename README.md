Detecting Fraud Transactions using the Credit Card Fraud Detection dataset (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

Used scikit-learn's machine learning models for prediction. Logistic Regression, Random Forest, Support Vector Machine, XGBoost, Ridge Classifier and SGD Classifiers were run.

Obtained the following results:

Classifiers:  LogisticRegression has a score of 98.0 % accuracy score
Classification Report: 
               precision    recall  f1-score   support

           0       1.00      0.98      0.99     56866
           1       0.06      0.88      0.12        96

    accuracy                           0.98     56962
   macro avg       0.53      0.93      0.55     56962
weighted avg       1.00      0.98      0.99     56962

Confusion Matrix: 
 [[55588  1278]
 [   12    84]] 

Classifiers:  RandomForestClassifier has a score of 100.0 % accuracy score
Classification Report: 
               precision    recall  f1-score   support

           0       1.00      1.00      1.00     56866
           1       0.97      0.72      0.83        96

    accuracy                           1.00     56962
   macro avg       0.99      0.86      0.91     56962
weighted avg       1.00      1.00      1.00     56962

Confusion Matrix: 
 [[56864     2]
 [   27    69]] 

Classifiers:  RidgeClassifier has a score of 99.0 % accuracy score
Classification Report: 
               precision    recall  f1-score   support

           0       1.00      0.99      0.99     56866
           1       0.10      0.83      0.17        96

    accuracy                           0.99     56962
   macro avg       0.55      0.91      0.58     56962
weighted avg       1.00      0.99      0.99     56962

Confusion Matrix: 
 [[56117   749]
 [   16    80]] 

Classifiers:  SGDClassifier has a score of 96.0 % accuracy score
Classification Report: 
               precision    recall  f1-score   support

           0       1.00      0.96      0.98     56866
           1       0.04      0.89      0.07        96

    accuracy                           0.96     56962
   macro avg       0.52      0.92      0.53     56962
weighted avg       1.00      0.96      0.98     56962

Confusion Matrix: 
 [[54701  2165]
 [   11    85]] 

Classifiers:  SVC has a score of 100.0 % accuracy score
Classification Report: 
               precision    recall  f1-score   support

           0       1.00      1.00      1.00     56866
           1       0.58      0.71      0.64        96

    accuracy                           1.00     56962
   macro avg       0.79      0.85      0.82     56962
weighted avg       1.00      1.00      1.00     56962

Confusion Matrix: 
 [[56817    49]
 [   28    68]] 

Classifiers:  XGBClassifier has a score of 100.0 % accuracy score
Classification Report: 
               precision    recall  f1-score   support

           0       1.00      1.00      1.00     56866
           1       0.97      0.75      0.85        96

    accuracy                           1.00     56962
   macro avg       0.99      0.87      0.92     56962
weighted avg       1.00      1.00      1.00     56962

Confusion Matrix: 
 [[56864     2]
 [   24    72]] 

