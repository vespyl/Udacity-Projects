# Loan Data
## by Vicente Peña y Lillo


## Dataset

The dataset contains 113,937 loans with 81 variables, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

## Summary of Findings

We consider the following features to analyse: Term, BorrowerRate,ListingCategory (numeric), EmploymnetStatus, EmploymnetStatusDuration, BorrowerState, Occupation, IncomeRange, IncomeVerifiable, TotalProsperPaymentsBilled and OnTimeProsperPayments. This features are gathered when the loan application is made, so they can apport insights to risk of being paid ('ProsperScore').

Impliying that the following features make a borrower less risky :
    * High income
    * Studies listing category
    * Low interest rate
    * Verified income
    * 12 month term

Also, on time payments of past loans doesn't correlate with the borrower risk.

## Key Insights for Presentation

The one of the main thoughts that people had at the moment of lending money is if they are going to paid back. So the main focus of this explanatory analysis is to determine wich features has relation with the risk of the borrowers.

For the reason explained before and after the exploratory analysis, were chosen the following figures:

* The distribution of the BorrowerRate, OnTimeRatio and EmploymentStatusDuration, and their relationship with the variable of interest ProsperScore. 

    > Chosen because their condition of continous variables and commonly thought of clear relation with the borrower risk.

* The relationship between the EmploymentStatus and IncomeRange vs the variable of interest ProsperScore.

    > Chosen and arranged together because they relate to each other and showna clear relationship with the variable of interest.

* The highest and lowest states according to there borrowing rate.

    > This figure show a shockinly relationship between the state and the interest rate.

* The highest and lowest scored occupations correlated to BorrowerRate and ProsperScore.

    > Figure prooving that the occupation relate with the borrowing rate and the prosper score. 