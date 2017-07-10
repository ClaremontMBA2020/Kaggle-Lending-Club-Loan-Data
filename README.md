# Predictive model of default clients.

Here you can find some machine learning techniques in classification problem. 
Data: https://www.kaggle.com/wendykan/lending-club-loan-data

The task was to build a predictive model of default client with loan_status variable. 

In this repository you can find three approaches:

- *solution*: I chose some models, did cross-validation to know the best parameters and then ensembled them together,
- *solution_simplify*: Because of my computer's weak component and lack of memory I decided to simplify preceding idea: I chose 3 models with default parameters, trained them on the train set, calculated metrcs and then chose the best model (using F1 score, because classes in target column are imbalanced),
- *solution_xgboost*: I used xgboost which is the most used model in Kaggle's competitions. It's super fast and super effective.
