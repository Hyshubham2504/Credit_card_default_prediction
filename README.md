
                                    Credit Card Default Prediction (2022)
Objective
The Credit Card Default Prediction project aims to leverage the previous 6 months of payment history to predict customers who might default in upcoming months. Dealing with class imbalance using the SMOTE technique, the Gradient Boosting algorithm on the SMOTE dataset demonstrated the best result with an accuracy of 77% and a recall value of 0.48. This project provides valuable insights into credit risk management.

About the Dataset
Dataset Information
The dataset covers credit card clients in Taiwan from April 2005 to September 2005, encompassing demographic factors, credit data, and payment history. It comprises 25 variables, including repayment status, bill statements, and payment amounts.

Key Variables
ID: ID of each client
LIMIT_BAL: Amount of given credit in NT dollars
SEX: Gender (1=male, 2=female)
EDUCATION: Education level
MARRIAGE: Marital status
AGE: Age in years
PAY_0 to PAY_6: Repayment status from April to September 2005
BILL_AMT1 to BILL_AMT6: Bill statement amounts
PAY_AMT1 to PAY_AMT6: Previous payment amounts
default.payment.next.month: Default payment (1=yes, 0=no)
Project Title: Predicting Credit Card Default
Problem Description
This project focuses on predicting cases of customers defaulting on credit card payments in Taiwan. The predictive accuracy of estimated default probabilities is emphasized for effective risk management. The K-S chart is utilized to evaluate which customers are likely to default on their credit card payments.

Goal and Plan
The primary goal is to predict customers' default status with a month of advance. The notebook is structured to cover initial exploration, cleaning, feature engineering, and a final result analysis. The project also explores blind machine learning, addressing pitfalls in the process.

Insights and Lessons Learned
This notebook serves as a learning tool for data manipulation and machine learning techniques. It covers the challenges of class imbalance, the impact of feature importance (with repayment status and bill statement standing out), and the effectiveness of the SMOTE technique in handling imbalanced datasets.

For detailed insights and lessons learned, refer to the project's documentation and code files available in the repository.
