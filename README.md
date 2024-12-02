# IML_proj

Loan Default Prediction Using Machine Learning
Project Overview
Objective: Predict loan defaults using machine learning models to assist financial institutions in minimizing risks and enhancing decision-making processes.
Key Features: Exploratory Data Analysis (EDA), Feature Engineering (Clustering and Regularization), and Evaluation of multiple models (Logistic Regression, GDA, KNN, Naive Bayes).
Dataset: Real-world dataset sourced from Kaggle containing 94,448 loan applications with borrower financial details and loan characteristics.
Link to the Kaggle Data Set: https://www.kaggle.com/code/nidhaljegham/default-loan-prediction-96-accuracy/input?select=train.csv
Table of Contents
Importing necessary libraries
Loading the Dataset
Exploratory Data Analysis (EDA)
Distribution of Target Variable
Correlation Heatmap
Distribution of Numerical Column
Distribution of Categorical Column
Correlation analysis of categorical columns with Target Variable
Feature Selection Process
Building Initial Logistic Regression Model
Building Initial Gaussian Discriminant Analysis Model
K-Means Clustering
Expectation Maximisation for Mixture of Gaussians
Building new Logistic Regression model
Handling Class Imbalance with SMOTE
Logistic Regression Model post changes
k_Fold Cross-Validation Setup
K-Nearest Neighbours model (KNN)
Naive Bayes
L1 Regularisation (Lasso) for Feature Selection
Elastic Net for Feature Selection
Logistic Regression with L2 Regularisation
Gaussian Discriminant Analysis (GDA)

Columns Breakdown:
ID: Unique Identity number for each loan disbursed by the bank
Loan_Title: Reason for the loan
Application Type: indicates when the representative is an individual or joint
Loan_Amount: Amount of loan that has been disbursed to the applicant
EMI: Equated Monthly Installments is basically the total amount of money that the applicant needs to pay to repay the entire loan in the stipulated time period. 
Term_of_loan: Tenure of the loan i.e. in how much time it needs to be completely repaid (principal amount + interest)
Annual_InterestRate: Interest Rate charged by the bank for the Loan Amount. 
Monthly_InterestRate: Annual_InterestRate divided by 12. 
Monthly_Household_Income: Sum of the monthly income earned by each member of the family. 
Debt_to_Income: ratio of representative's total monthly debt repayment divided by monthly income excluding mortgage
Grade: grade by the bank
Home_Ownership
Delinquency_2years
Inquires_6months: 
Lastweek_pay: indicates how long (in weeks) a representative has paid EMI after batch enrolled
Loan_Status: 0 = Non-Defaulter; 1 = Defaulter
