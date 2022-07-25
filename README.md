# Machine-Learning-Summer-Training-Hackathon-2022
Loan Default Prediction

Can you predict if an applicant will default the loan or not in the future?



Problem Statement

MyHom is a finance company that lends housing loans at the best and most affordable interest rates to customers. In recent times, the company incurred heavy losses due to loan defaults. Most applicants failed to repay the loan as per the promissory note.


In order to avoid such losses, the company has decided to build a system for identifying the loan defaulters automatically based on data. This will help the company to identify the potential applicants and ensure the smooth running of the entire process.


Now, the company challenges the Data Science community to build a smart AI system to predict the probability of an applicant defaulting the loan or not in the future.



About the Dataset


You are provided with the past applicant’s data containing the demographic information, loan attributes, and target variable indicating if an applicant will default the loan or not.



Data Dictionary


You are provided with 3 files - train.csv, test.csv, and sample_submission.csv



Train and Test Data


The train and test set contains the different attributes related to demographic and loan information of the applicants such as age, profession, no. of active loans, loan default in previous loans, and so on. The training set contains the target variable loan_default and you need to predict the target variable in the test set.



Variable

Description

loan_id

Unique identifier of a loan

age

Age of the Applicant

Education

Applicant Education

proof_submitted

Type of proof submitted

loan_amount

Loan Amount Disbursed

asset_cost

The total asset value of the applicant

no_of_loans

No. of the loans taken by the applicant 

no_of_curr_loans

No. of active loans held by the applicant

last_delinq_none

The loan defaulted in at least one of the past loans

loan_default (Target Variable)

0/1 indicating if an applicant will default the loan or not




Submission File Format


sample_submission.csv contains 2 variables - 



Variable

Description

loan_id

Unique Identifier of a loan

loan_default

0 or 1 indicating if an applicant will default the loan or not




Evaluation metric


The evaluation metric for this hackathon would be the macro F1 Score.



Public and Private Split


Test data is further divided into Public (40%) and Private (60%) data.


Your initial responses will be checked and scored on the Public data. The final rankings would be based on your private score which will be published once the competition is over.
