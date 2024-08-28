# Lending Club Case Study



## Problem statement
Lending club is a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision.
1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
###  Objective
The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. Using exploratory data analysis (EDA) this objective needs to be achieved with the help of dataset which has information about past loan applicants.

The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

## Conclusions
* Lending club should reduce the high interest loans for 60 months tenure, they are prone to loan
default.
* Grades are good metric for detecting defaulters. Lending club should examine more information
from borrowers before issuing loans to Low grade (G to A).
* Lending Club should control their number of loan issues to borrowers who are from CA, FL and
NY to make profits.
* Small business loans are defaulted more. Lending club should stop/reduce issuing the loans to
them.
* Borrowers with mortgage home ownership are taking higher loans and defaulting the approved
loans. Lending club should stop giving loans to this category when loan amount requested is more
than 12000.
* People with more number of public derogatory records are having more chance of filing a
bankruptcy. Lending club should make sure there are no public derogatory records for borrower.

## Technologies Used
- Python - 3.12.4
- NumPy version - 1.26.4
- pandas version - 2.2.2
- Matplotlib version - 3.8.4
- Seaborn version - 0.13.2


