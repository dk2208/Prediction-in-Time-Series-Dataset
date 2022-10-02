# Prediction in Time Series Dataset

- Objective is to provide prediction values of Para 9-13 for the 10th year of each section based on the provided dataset.

## Input File

- Given dataset contains 1009 rows and 15 columns in which first column denotes each road section, second column denotes the year number for which parameter values are recorded and columns 3 to 15 represents values for parameters 1 to 13.

## Model Used

- Random Forest Regressor model used with GridSearchCV.
- GridSearchCV performs hyperparameter tuning, i.e, find the best parameter values for implementing Random Forest Regressor which then predicts the values.
- Hyperparameter tuning helps in maximizing model's predictive accuracy.

## Result

- Root Mean Square Error(RMSE) value of model is 61.3257.
