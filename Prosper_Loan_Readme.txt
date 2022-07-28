# Data Analysis Of Prosper Loan
Prosper is a peer-to-peer lending market place in the united states founded in the year 2005. Through Prosper, people can invest in each other in a way that is financially and socially rewarding. Borrowers apply online for a fixed-rate, fixed-term loan between 2000dollars and 40000dollars. Individuals and institutions can invest in the loans and earn attractive returns. Prosper handles all loan servicing on behalf of the matched borrowers and investors.


## Data
The prosper loan dataset has a record of 113937 loan applications taken from 2009 to 2014 with 81features. However, 15 of these features would be selected for this analysis. The main feature of interest would be the loan original amount and investors. The dataset can be found in this link https://docs.google.com/document/d/e/2PACX-1vQmkX4iOT6Rcrin42vslquX2_wQCjIa_hbwD0xmxrERPSOJYDtpNc_3wwK_p9_KpOsfA6QVyEHdxxq7/pub.


## Summary Of Findings
During exploration of the data, I was able to discover that the total amount of loan issued each month has continue to enjoy a steady growth. This might be as a result of more people finding prosper loan attractive for their loan needs. Invariable, investor yield started with an initial growth, peaked at some point then started experiencing decline. I want to believe this is strategic inorder to make prosper loan more appealing to potential loan applicants. A lower loan yield implies lower interest rate on the loan.

There are some factors that affect the interest rate on loan. One of such is the loan original amount. As the loan original amount increases, the interest rate reduces. Large loans, tend to have lower interest rate as compared to smaller loans. Another factor is the monthly loan payment. The larger the monthly loan payment, the smaller the interest rate. 

In most cases, the monthly loan payment plan is less than $500. However, for income earners above $75000, the monthly payment plan can go above 500dollars. Short term loans have a high repayment plan than that of long term loans.

One surprising discovering I made is seeing that the number of investors needed to fund a 36months loan is actually higher than that of a 60months loan. In general, there is an inverse relationship between the number of investors and the loan original amount. Visualizing this relationship for each loan term, reveals that 36months loan need more investors than 60months loan.


## Key Insights For Presentation.
The presentation started with gaining insight into the four main features of the dataset which include LoanOriginalAmount, BorrowerAPR, Investors and LenderYield using a histogram. Then, trends in the growth of loan amount was revealed using pointplots.

Scatter plot with a regression line was plotted to see the relationship between most of this variables. Finally, a barchart was used to reveal if loan size affects the interest rate on loan.

