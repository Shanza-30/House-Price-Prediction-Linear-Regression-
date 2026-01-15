House Price Prediction

This project predicts house prices using the Kaggle House Prices: Advanced Regression Techniques dataset.
The goal is to build a clean machine learning pipeline and evaluate it using RMSE.

Dataset

Files used:
train.csv – Training data with target SalePrice
test.csv – Data for final prediction
sample_submission.csv – Submission format
data_description.txt – Column explanations

Steps Performed

1. Data Understanding
   
Viewed data using head(), info(), describe(), and shape
Identified numeric and categorical features

3. Data Cleaning

Filled missing numeric values with mean
Filled missing categorical values with mode

5. Feature Encoding
   
Converted categorical variables using one-hot encoding

6. Feature Engineering
   
Created new features like:
TotalArea
TotalBath

8. Outlier Handling
   
Removed extreme values from living area vs price

10. Model Training
    
Used Linear Regression
Split data into train and validation sets

12. Evaluation
    
Evaluated using RMSE
Applied cross-validation for stable results

14. Prediction

Generated predictions on test data
Created final submission file

Model Used

Linear Regression
Evaluation Metric: RMSE

Output

Trained model
RMSE score printed
final_submission.csv file ready for Kaggle upload

Conclusion

This project shows the complete workflow of a machine learning regression problem:
from data understanding and cleaning to feature engineering, modeling, and evaluation.
