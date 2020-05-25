# Credit Card Fraud Detection

Background : 
The dataset contains transactions made by credit cards in September 2013 by european cardholders.This dataset presents transactions that 
occurred in two days and is highly imbalanced. However the features or predictors are not revealed due to privacy reasons.

Aim : To build a prediction model for this Binary Classification problem and see how prediction score changes for each model in predicting 
whether a transaction is fradulent or not

Synopsis:
1. Exploratory Data analysis is done to understand the data
2. For data wrangling scikit learn pipelines are used
3. The dataset is IMBALANCED with the minority class 0.98%(Fradulent Transaction or positive class) and the majority class at 99.018%.
Here our class of interest is the minority or positive class.
4. Also since it is appropriate to give more weightage to Recall to minimize "False Negatives", I used F2 score as my evaluation metric
5. Since the data is highly imbalanced, Cost sensitive methods and data Sampling algorithms like SMOTE, SVMSMOTE and ADASYN are used
6. Different hyper tuning parameters are tried wherever possible
7. Joblib is used for saving and uploading models 
8. Ensembling methods including stacking and voting, Light GBM and neural network from sckit learn MLP classifier has also been tried in the 
process of finding the best model

