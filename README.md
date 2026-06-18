# Bank Marketing Deposit Prediction

## Project Overview

This project aims to predict whether a bank customer will subscribe to a term deposit based on customer demographic information, financial details, and previous marketing campaign interactions.

The project applies multiple Machine Learning classification algorithms and compares their performance to identify the best model for prediction.

---

## Business Problem

Banks spend significant resources contacting customers during marketing campaigns. Predicting which customers are likely to subscribe to a term deposit helps reduce marketing costs and improve campaign efficiency.

The objective of this project is to build a machine learning model that predicts whether a customer will subscribe to a term deposit.

Target Variable:

* Deposit = Yes (Customer subscribed)
* Deposit = No (Customer did not subscribe)

---

## Dataset

Bank Marketing Dataset

Features include:

* Age
* Job
* Marital Status
* Education
* Balance
* Housing Loan
* Personal Loan
* Contact Type
* Campaign Information
* Previous Marketing Outcomes

Target Column:

* Deposit

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Outlier Detection and Treatment
5. Feature Encoding
6. Train-Test Split
7. Model Building
8. Hyperparameter Tuning using GridSearchCV
9. Model Evaluation
10. Model Comparison

---

## Algorithms Used

* Logistic Regression
* Decision Tree
* Random Forest
* Bagging Classifier
* AdaBoost
* Gradient Boosting
* XGBoost
* LightGBM
* Support Vector Machine (SVM)

---

## Evaluation Metrics

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* Cross Validation Score

---

## Best Model Performance

XGBoost (Tuned)

* Accuracy: 85.52%
* Precision: 83.59%
* Recall: 86.87%
* F1 Score: 85.20%

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn
* XGBoost
* LightGBM
* Jupyter Notebook

---

## Conclusion

Multiple machine learning models were trained and compared on the Bank Marketing dataset. Hyperparameter tuning was performed using GridSearchCV to improve model performance. Among all the models tested, XGBoost achieved the best results with an accuracy of 85.52%, making it the most effective model for predicting customer deposit subscriptions.

---

## Author

V. Narasimha Reddy

B.Tech Data Science

St. Peter's Engineering College
