# Prosper Loan Data Exploration
## by Olaoluwa Ebiekuraju


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount,
borrower rate (or interest rate), current loan status, borrower income, and many others.
The dataset can be found in the Udacity classroom[here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv),
with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings

In this exploration, I found there was a strong relationship between the Prosper rating and the Loan amount, 
Prosper rating and the Income of the borrower. Others include; Loan amount and Length of the loan, 
Loan amount and the quarter the Loan was borrowed. Those with high income have better ratings. 
The average loan amount borrowed in the first and last quarters were higher than those in the middle half of the year 
and When I isolated the ralatinship between the loan amount and the quarter across each income range, it showed
that those who earn 50k and above borrowed more money in the first and the last quarter. Also, home owners has better
Proper Rating than those who own no home. I verified the relationship between monthly payment and loan amount. 
The scatter plot showed a linear relationship (i.e as loan amount increases, monthly payment also increase)
but splited into three major divisions. Using color encoding to delineate the length of loan in the scatter plot,
it showed that monthly payment icreases with loan amount and decreases with the loan lenth.

Outside of the main variables of interest, I also verified the relationship between length of loan and the quarter. 
From the last quarter of 2005 upto the end of 2010 all loan lasted for 36 months and even after. However, there was 
a significant increase in the loans lasting for 60 months from 2012 to 2014.

## Key Insights for Presentation

For the presentation, I focus on just the main factors associated with the monthly payment and the loan amount
leaving out most of the intermediate derivations. I start by introducing the monthly payment variable, follow by
the pattern in loan amount distribution, then plot the scatterplot. I introduce the term of the loan (Loan Length) 
and plotted the scatter plot, encoding the loan length with different colors.

Afterwards, I introduce the Quarter and the Income Range categories. To start, I plotted the boxplots of loan amount 
and Quarter, and loan amount and Income Range. Finally, I plotted boxplots of loan amount and quarter by the income range.
