# IML_proj

Loan Default Prediction Using Machine Learning

Project Overview
1. Objective: Predict loan defaults using machine learning models to assist financial institutions in minimizing risks and enhancing decision-making processes.
2. Key Features: Exploratory Data Analysis (EDA), Feature Engineering (Clustering and Regularization), and Evaluation of multiple models (Logistic Regression, GDA, KNN, Naive Bayes).
3. Dataset: Real-world dataset sourced from Kaggle containing 94,448 loan applications with borrower financial details and loan characteristics.

Link to the Kaggle Data Set: https://www.kaggle.com/code/nidhaljegham/default-loan-prediction-96-accuracy/input?select=train.csv

Table of Contents
1. Importing necessary libraries
2. Loading the Dataset
3. Exploratory Data Analysis (EDA)
4. Distribution of Target Variable
5. Correlation Heatmap
6. Distribution of Numerical Column
7. Distribution of Categorical Column
8. Correlation analysis of categorical columns with Target Variable
9. Feature Selection Process
10. Building Initial Logistic Regression Model
11. Building Initial Gaussian Discriminant Analysis Model
12. K-Means Clustering
13. Expectation Maximisation for Mixture of Gaussians
14. Building new Logistic Regression model
15. Handling Class Imbalance with SMOTE
16. Logistic Regression Model post changes
17. k_Fold Cross-Validation Setup
18. K-Nearest Neighbours model (KNN)
19. Naive Bayes
20. L1 Regularisation (Lasso) for Feature Selection
21. Elastic Net for Feature Selection
22. Logistic Regression with L2 Regularisation
23. Gaussian Discriminant Analysis (GDA)

Columns Breakdown:
1. ID: Unique Identity number for each loan disbursed by the bank
2. Loan_Title: Reason for the loan
3. Application Type: indicates when the representative is an individual or joint
4. Loan_Amount: Amount of loan that has been disbursed to the applicant
5. EMI: Equated Monthly Installments is basically the total amount of money that the applicant needs to pay to repay the entire loan in the stipulated time period.
6. Term_of_loan: Tenure of the loan i.e. in how much time it needs to be completely repaid (principal amount + interest)
7. Annual_InterestRate: Interest Rate charged by the bank for the Loan Amount.
8. Monthly_InterestRate: Annual_InterestRate divided by 12.
9. Monthly_Household_Income: Sum of the monthly income earned by each member of the family.
10. Debt_to_Income: ratio of representative's total monthly debt repayment divided by monthly income excluding mortgage
11. Grade: grade by the bank
12. Home_Ownership
13. Delinquency_2years
14. Inquires_6months:
15. Lastweek_pay: indicates how long (in weeks) a representative has paid EMI
16. Loan_Status: 0 = Non-Defaulter; 1 = Defaulter
