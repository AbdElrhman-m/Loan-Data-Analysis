# Loan Data Exploration
##  by [AbdElrhman Mohamed](https://www.linkedin.com/in/abdelrhman-m/)

##  Status
[![Build Status](https://img.shields.io/travis/twbs/bootstrap/v4-dev.svg)](https://github.com/superbido/fav-moviewebsite/edit/master/README.md)

## Dataset

> we have data from Prosper which was founded in 2005 as the first peer-to-peer lending marketplace in the United States. and the data of about 110,000 loans from 2005-2014 and the data contains 'Term', Loan Status, Borrower Rate, Estimated Loss, Estimated Return, loan orginal amount and much more. 

>you can download it from [Here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)


## Summary of Findings

> 'EstimatedLoss' and 'EstimatedReturn' dimensions are all highly correlated with one another, and all of them are also highly correlated with 'BorrowerRate' Since BorrowerRate is a measure of loan cost, it's not too surprising that the overall trend between BorrowerRate and the two individual estimations.

> the best loan cost features (propserRatting AA, term 12, in the Q1 of the year, for customers(brorrwer) income  +100,000 USD) seem to get the Lowest cost of the loan.

> we can see that `C` rate takes the most loans even when The terms, income range or Quarter of year vary.

> the Estimatedloss increases as borrower_rate increases,
as well as the lowesr borrower rate for the people withincome +100,000\\$ and the Estimated Loss is none for those people.


## Key Insights for Presentation

For the presentation, I focus on the insights that helping person to choose When and how to get a loan with the least interest rate possible as :
> What affects the interest rate.

> the time best time to get alone.

>  best length of the loan expressed in months.

## What do u need to install for running this Ipython notebook?
>* python 3
* jupyter notebooks 
* anaconda
* pandas
* NumPy
* Matplotlib
* seaborn
