# House-Price-Prediction
## Regression Project:
To predict the prices of houses based on certain features.

## Models Used:
Multiple Linear Regression, XGBoost & Random Forest Regressor (Best)

## Files Description:

• train.csv - the training set (1460 rows x 81 columns)

• test.csv - the test set (1459 rows x 80 columns), has no target variable

• final_submission_test_dataset.csv - Contains the predicted values of "test.csv" dataset which were predicted using the model trained

   on "train.csv" dataset (1459 rows x 2 columns: one col is "House Id" and other is "Sale Price" for each house)

## Main Highlights:
• Used Standard Scaler for Feature Scaling, One Hot Encoding to convert categorical variables to Numerical Variables

• Dealt with null values: 

  ⦾ Removed All those columns which have more than 50 % null values 
    
  ⦾ Used "mean" to fill null values in remaining numerical variables 
  
  ⦾ Used "mode" to fill null values in remaining categorical variables variables 
