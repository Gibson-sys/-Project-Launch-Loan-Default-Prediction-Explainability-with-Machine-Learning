A machine learning project for predicting loan default using borrower data. 
Includes data preprocessing, modeling, evaluation, and SHAP explainability for feature impact analysis.
# Loan Default Prediction: Explainability with Machine Learning

## Project Overview

This project aims to predict loan default status using machine learning algorithms, with an emphasis on model explainability. The dataset includes various attributes like personal details, loan characteristics, and credit scores, and the goal is to predict whether a borrower will default on their loan.

### Key Features:
- **Predict Loan Default**: Classify loan applicants into defaulters and non-defaulters.
- **Explainability**: Use SHAP (SHapley Additive exPlanations) to understand the model's predictions.

---

## Dataset

The dataset contains the following columns:

- **person_age**: Age of the applicant
- **person_gender**: Gender of the applicant
- **person_education**: Educational background
- **person_income**: Annual income of the applicant
- **person_emp_exp**: Employment experience (in years)
- **person_home_ownership**: Whether the applicant owns a home or not
- **loan_amnt**: Amount of the loan requested
- **loan_intent**: Purpose of the loan (e.g., education, home improvement)
- **loan_int_rate**: Interest rate of the loan
- **loan_percent_income**: Percentage of income required for loan repayment
- **cb_person_cred_hist_length**: Length of the applicant's credit history
- **credit_score**: Applicant's credit score
- **previous_loan_defaults_on_file**: Whether the applicant has defaulted on previous loans
- **loan_status**: Actual loan status (0 = No default, 1 = Default)

---

## Objective

The goal of this project is to:
1. Build a machine learning model that can predict the likelihood of a loan applicant defaulting on their loan.
2. Evaluate the impact of various features like credit history, income, and loan characteristics on the loan default prediction.
3. Ensure model interpretability using SHAP to explain the predictions.

---

## Steps Involved

### 1. Data Preprocessing
- Handle missing values and encode categorical variables (e.g., `person_gender`, `loan_intent`).
- Scale numerical features (e.g., `loan_amnt`, `person_income`) to improve model performance.

### 2. Model Training
- Split the dataset into training and testing sets.
- Train various models like **Logistic Regression**, **Random Forest**, and **XGBoost** to predict loan default status.
- Evaluate the models using metrics like **accuracy**, **precision**, **recall**, and **F1-score**.

### 3. Explainability with SHAP
- Use SHAP to explain the contributions of individual features to the model's predictions.
- Visualize how the model arrives at its decision for loan approval or rejection.

---

## Installation and Setup

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Gibson-sys/Project-Launch-Loan-Default-Prediction-Explainability-with-Machine-Learning.git
