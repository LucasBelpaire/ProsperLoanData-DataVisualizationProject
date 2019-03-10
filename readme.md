# Prosper Loan Data Exploration
## by Lucas Belpaire


## Dataset

This document explores the 'Prosper Loan Data' dataset. This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1551779160008000).
An explanation of all variables can be found [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing).

## Summary of Findings

During the exploration a limited amount of variables where examined: LoanStatus, Recommendations, DebtToIncomeRatio, IncomeVerifiable, StatedMonthlyIncome, ProsperScore, ProsperRating (alpha), BorrowerRate, Listing Category, EmploymentStatus, LoanOriginalAmount.

It was quickly clear that the variables 'IncomeVerifiable', 'Recommendations', 'Listing Category' and 'EmploymentStatus' were not interesting to explore any further.

It was surprising to see that, when looking at all loans that have ended, almost a fourth had failed to have been paid back.

The less risky loans are less popular.

Small loans are also much more popular than large ones.

It is surprising to see that there is no correlation between StatedMonthlyIncome and LoanOriginalAmount.

To increase the chance of a completed loan, the variables to increase are: 'ProsperScore', 'StatedMonthlyIncome', 'ProsperRating'.

Lowering the following variables will also result in a higher chance to complete the loan: 'Term', 'BorrowerRate'.

## Key Insights for Presentation

The presentation focusses on the variables that positively affect the chance that a loan will be completed succesfully.

We start with showing the distrubution of the different Loan Statuses. After which the distribution of the Prosper Ratings is shown.

Then, using a histogram, it is shown that a higher Prosper Rating correlates with a higher percentage of completed loans.

The presentation ends with a scatterplot that combines three variables: Prosper Score, Borrower Rate and Loan Status. This plot confirms our earlier findings. That a higher Prosper Score and a lower Borrower Rate correlates with a higher amount of completed loans.