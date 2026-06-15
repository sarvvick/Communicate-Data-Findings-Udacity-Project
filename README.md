# Prosper Loan Dataset Exploration

## Overview

This project performs Exploratory Data Analysis (EDA) on the Prosper Loan Dataset to identify key factors that influence loan pricing and borrower risk. The analysis investigates relationships between borrower characteristics, loan attributes, credit scores, and Annual Percentage Rate (APR).

## Dataset

The Prosper Loan Dataset contains **113,937 loan records** with **81 features** describing borrower information, credit history, loan details, and repayment outcomes.

Key features used in this analysis include:

* Borrower APR
* Prosper Score
* Loan Original Amount
* Employment Status
* Stated Monthly Income
* Credit Score Range
* Income Range
* Loan Status
* Loan Term

## Project Objectives

* Explore the distribution of borrower APR and loan amounts.
* Analyze how borrower characteristics affect loan pricing.
* Identify relationships between credit scores, income, loan amount, and APR.
* Understand factors associated with borrower risk and loan performance.

## Data Wrangling

The dataset was cleaned by:

* Selecting relevant loan and borrower-related features.
* Removing records with missing values.
* Creating an Average Credit Score feature from credit score ranges.
* Preparing a subset dataset for analysis and visualization.

## Exploratory Analysis

### Univariate Analysis

* Borrower APR is concentrated between **10% and 25%**.
* Loan amounts show a right-skewed distribution.
* Most borrowers in the dataset are employed.

### Bivariate Analysis

Key findings:

* Higher loan amounts generally correspond to lower APR.
* Higher Prosper Scores are associated with lower borrower APR.
* Higher-income borrowers tend to receive lower APR rates.

### Multivariate Analysis

Further investigation revealed:

* Borrowers with high Prosper Scores receive lower APR even for larger loan amounts.
* Prosper Score strongly influences loan pricing.
* Credit score and income jointly contribute to favorable borrowing terms.
* Loan amount exhibits a negative relationship with APR.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook


## Key Insights

* Prosper Score is one of the strongest predictors of borrower APR.
* Higher creditworthiness results in significantly lower borrowing costs.
* Income and employment status influence loan pricing and approval likelihood.
* Larger loans tend to be offered at lower APR rates compared to smaller loans.

## Future Work

* Build predictive models for loan default risk.
* Perform feature engineering on borrower credit history.
* Develop machine learning models for APR prediction.
* Compare borrower behavior across loan status categories.

