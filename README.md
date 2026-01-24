# 🏠 House Price Prediction using Machine Learning

This project predicts house prices using the **Kaggle – House Prices: Advanced Regression Techniques** dataset. It focuses on building a **clean, end-to-end machine learning pipeline** and evaluating model performance using **Root Mean Squared Error (RMSE)**, a standard regression metric.


## 🎯 Project Objective

The primary objective of this project is to understand and implement the **complete workflow of a regression problem**, including data preprocessing, feature engineering, model training, evaluation, and generating predictions for real-world submission.


## 📂 Dataset Information

The following files from the Kaggle dataset are used:

* **train.csv** – Training dataset containing features and the target variable `SalePrice`
* **test.csv** – Test dataset for generating final predictions
* **sample_submission.csv** – Required submission format for Kaggle
* **data_description.txt** – Detailed explanation of all features


## 🛠️ Steps Performed

### 1️⃣ Data Understanding

* Explored the dataset using `head()`, `info()`, `describe()`, and `shape()`
* Identified **numerical** and **categorical** features
* Analyzed feature distributions and missing values


### 2️⃣ Data Cleaning

* Filled missing **numerical values** using the **mean**
* Filled missing **categorical values** using the **mode**
* Ensured no null values remained before modeling


### 3️⃣ Feature Encoding

* Converted categorical variables into numerical format using **One-Hot Encoding**
* Ensured consistency between training and test datasets


### 4️⃣ Feature Engineering

Created new meaningful features to improve model performance:

* **TotalArea** – Combined area of important house spaces
* **TotalBath** – Total number of bathrooms (full + half)

These features help capture the overall size and usability of the house.


### 5️⃣ Outlier Handling

* Removed extreme outliers from **living area vs. sale price**
* Improved model stability and reduced prediction error


### 6️⃣ Model Training

* Applied **Linear Regression** as the baseline model
* Split data into **training and validation sets**
* Trained the model on processed features


### 7️⃣ Model Evaluation

* Evaluated model performance using **RMSE**
* Applied **cross-validation** to ensure stable and reliable results
* Printed RMSE score for performance assessment


### 8️⃣ Prediction & Submission

* Generated predictions on the test dataset
* Created a final submission file:

  ```
  final_submission.csv
  ```
* File is ready for direct upload to Kaggle


## 🧠 Model Used

* **Linear Regression**
* **Evaluation Metric:** RMSE


## 📦 Output

* Trained regression model
* RMSE score displayed in output
* `final_submission.csv` for Kaggle submission


## 🔮 Future Improvements

* 🔄 Try advanced models like **Ridge, Lasso, Random Forest, XGBoost**
* 📊 Perform feature importance analysis
* 📈 Apply log transformation on target variable
* 🤖 Use pipelines for cleaner preprocessing and modeling


## 📌 Conclusion

This project demonstrates a **complete and structured approach to solving a regression problem**, covering everything from data understanding and cleaning to feature engineering, model training, evaluation, and prediction. It serves as a strong foundation for advancing into **competitive machine learning and real-world regression tasks**.
