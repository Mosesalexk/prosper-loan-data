# Prosper Loan Data

## Dataset

This document explores a dataset containing information of 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, borrower employment status, borrower credit history, and the latest payment information. The data is available from https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1589992705023000
This links provides the details about the dataset. https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1589992705024000


## Summary of Findings

In the first stage, I was curious about the spread of APR. I have plotted the APR for different loans. I went on to check the correlation between different factors.

I found there is a negative correlation between apr and loan initial amount. 

With this correlation in mind , i have investigated further and found other factors that influence the loan apr.

Prosper rating is the major factor that determines the apr. Higher income groups tends to have better prosper rating. They tend to get higher loan amounts at lower apr.

Most of the debt are debt consolidation. One intresitng insight I have learned from this study is that, once we have AA prosper rating, we can take high initial loan amount,  debt consolidation loan a, with very low apr and and clear all our debts. This will be more profitable. Or we get the loan providers adjsut our apr accordingly. 


## Key Insights for Presentation


For the presentation, first i explained the spread of the apr.
Then presenteed the correlation between diffrent factors and correlation between intial loan amount abd apr stood out.
Further i present the relationship between apr, loan amount and other catergorical features.

Prosper Rating stood out. 

In the final slide i showed the heat map of correlation between apr and loan amount for each of the propser ratings. 

Conclusion. One single factor that contribute for the greates spread of APR is the Prosper Rating. Higher income groups tend to have better prosper rating. We can further study the database to determine other factors that determine the prosper rating. 
