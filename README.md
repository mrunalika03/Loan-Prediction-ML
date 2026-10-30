# Loan Prediction Using Machine Learning

## 1. Project Objective

The objective of this project is to predict whether a loan application will be approved or rejected based on applicant information using machine learning algorithms.

## 2. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 3. Dataset

This project uses two datasets:

- Loan Train.csv
- Loan Test.csv

The target variable is `Loan_Status`:

- Y – Loan Approved
- N – Loan Rejected

## 4. Project Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning and Preprocessing
4. Handling Missing Values
5. Categorical Encoding
6. Feature Scaling
7. Feature Engineering
8. Model Training
9. Model Evaluation
10. Final Loan Prediction

## 5. Machine Learning Algorithms

The following 10 algorithms were compared:

1. Logistic Regression
2. Linear Discriminant Analysis
3. K-Nearest Neighbors (KNN)
4. Decision Tree
5. Naive Bayes
6. Support Vector Machine (SVM)
7. Random Forest
8. AdaBoost
9. Gradient Boosting
10. Extra Trees

## 6. Best Performing Model

**K-Nearest Neighbors (KNN)**

Validation Results:

- Accuracy: 86.99%
- Macro F1 Score: 83.10%

## 7. Feature Engineering

Created a new feature called `Total_Income` by adding:

ApplicantIncome + CoapplicantIncome

## 8. Final Output

The selected KNN model was trained using the complete training dataset and used to predict loan statuses for 367 test applicants.

The predictions were saved in:

`Loan_Prediction_Submission.csv`

The trained model was saved in:

`loan_prediction_model.pkl`

## 9. Conclusion

This project demonstrates the application of machine learning classification algorithms to predict loan approval status.

Through this project, I learned data preprocessing, exploratory data analysis, model training, model evaluation, model comparison, and prediction using machine learning.