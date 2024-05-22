# Lending Club Case Study using EDA

## Problem Statement:

This analysis is for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.

Two types of risks are associated with the bank’s decision:

1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

## Business Objective:

 If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.So, the company wants to understand the driving factors (or driver variables) behind loan default.

## Expectations:

> Identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc

> Use the Exploratory Data Analysis to understand how consumer attributes and loan attributes influence the tendency of default.

## Business Understanding:

*We need to identify the driving factors for the loan applicants that are likely to default*

1. If the loan is in "current" state then the data points corresponding to it are not conclusive and can't determine the likeliness of the applicant to default. So, We need to analyze the applicants with loans that have reached a terminal state, which are the "Fully Paid" and "Charged Off" loans. So, we can give low priority to "current" state loan records or can ignore them in the analysis.

2. The Lending Club wants to understand the likeliness of the applicant to become default, before sanctioning the loan. So, the driving factors should be the data points that are available before the approval/sanction of the loan and the data points that are available only after sanctioning the loan can be disregarded in the analysis

libraries used :

1) numpy 
2) pandas 
3) matplotlib.pyplot 
4) seaborn 

Contributors:

* [Sarabjeet Singh](https://github.com/sarab1234)
* [Satish](https://github.com/satishkumarkatepalli)
