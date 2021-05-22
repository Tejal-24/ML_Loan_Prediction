# ML_Loan_Prediction

Using stratified cross validation technique the loan prediction dataset has beentrained and tested using below machine learning algorithms.

1. Logistic regression
    The training and test dataset are splitted into 5 folds. 
    The mean accuracy achieved is : 80.13%

2. Decision Tree
    The training and test dataset are splitted into 5 folds. 
    The mean accuracy achieved is : 70.84%
    
3. Random forest classifier
    Hyperparameter tuning for max_depth and n_estimators is performed. Then the model with best estimators is used for training and testing purpose.
    The best parameters are: max_depth = 9, n_estimator =81 
    The mean accuracy achieved is : 80.61%
    
4. XGBoost Classifier
    The training and test dataset are splitted into 5 folds.
    The mean accuracy achieved is : 80.21%
