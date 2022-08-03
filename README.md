# Part I - (Loan Data From Prosper)
## by (CHIMA CALEB C)

## Dataset Overview

> This dataset contains 113,937 loans records with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
In this investigation, I wanted to look at the characteristics of the data to answer the following questions
- What factors affect a loan’s outcome status?
- What affects the borrower’s APR or interest rate?
- Are there differences between loans depending on how large the original loan amount was?
`NB`:
This data (dictionary) explains the variables in the data set.
the Focus of this analysis is basically  on about 15 of the the features.

## Summary of Findings

> greater population of those who completed their laons borrowed smaller ammount,and also PAST DUE(91-120 days), DEFAULTED and CHARGEDOFF are relatively from those who borrowed higher amount, therefore LoanOriginalAmount has great impact on the loan status
Some other features includes (EmploymentStatus, EmploymentStatusDuration)

> Employment status:
The Employment status has great impact on the loan status, on a closer look i observed that those who are Not Employed, Retired and part-time dosent complet their laons.
and secondly Some of the distributions apears same though deffers in different aspect, they seem not to be cancealing loans for those that are Eemployed and self employed as well  they also have a greater population among others... the cancealliation of loan seem to be more for the Retired borrowers than others, therefore Employment status has great impact on the Status of the loan.

> the shape of the 'BorrowerAPR','BorrowerRate'and 'LenderYield' distributions are very similar to one another when plotted. The LenderYield distribution just looks slightly different since it takes a smaller range of values, further analysis showed they exist high correlation between them and the laon status.

## Key Insights for Presentation

>For the presentation, I focus on just the influence (Employment status, BorrowerSate,EmploymentStatusDuration, BorrowerAPR, LoanOriginalAmount and LoanStatus) of the data, and leave out most of the intermediate derivations. I start by introducing the EmploymentStatus then moved to the effect of Employment status on the LoanSatus, then i moved to the BorrowerSate with respect to their Annual Percentage Rate, i also discused the effect of Loan Original amount with respect to the loan status, and then finally the effect of the employment status duration with respect to the LoanStatus.