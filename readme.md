# (Prosper Loan)
## by (Amira Fathy)

 ## Prosper’s Story:
Prosper was founded in 2005 as the first peer-to-peer lending marketplace in the United States. Since then, Prosper has facilitated more than $13 billion in loans to more than 850,000 people.

Through Prosper, people can invest in each other in a way that is financially and socially rewarding. Borrowers apply online for a fixed-rate, fixed-term loan between  2,000𝑎𝑛𝑑  40,000. Individuals and institutions can invest in the loans and earn attractive returns. Prosper handles all loan servicing on behalf of the matched borrowers and investors.

Prosper Marketplace is backed by leading investors including Sequoia Capital, Francisco Partners, Institutional Venture Partners, and Credit Suisse NEXT Fund. https://www.prosper.com/about

## Dataset

>  the structure of your dataset:

The dataset contains 113,937 loans with 81 features .

and this is the variable Definitions:

https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0

i used just 20 columns  

['MemberKey','ListingCreationDate','LoanOriginalAmount','Term','LoanStatus','CreditGrade',
 'ProsperRating (Alpha)','IsBorrowerHomeowner','ListingCategory (numeric)','Occupation',
 'EmploymentStatus','EmploymentStatusDuration','BorrowerAPR','BorrowerState','BorrowerRate',
 'StatedMonthlyIncome','MonthlyLoanPayment','CurrentlyInGroup','TotalTrades','Investors']
 
 
 i divistion the data to two data before jule-2009 and after jule-2009
 
 created some columns extra like: (year ,listingcatorgry ) to use it later 
 

## Summary of Findings


conclusion: 

1- I found  the common  Term is 36 month, and the less one is  12 month 

2- I found the common year is 2013 and the less one  is 2009 

3- the common state CA (California) & the less ome is MD(Maryland) 

4- the common occupation is other and the second is professional

5- the common Employment status is employed it is more than half (60%)

6- there is no difference in percentage for the borrowers who have a home or the borrowers not have a home just (.4%)it is less than .5%

7- **c** is the most common risk ratio from 2005 to 2014

8- Debt consolidation is the common reason to do a loan .

9- the current & completed are bigger than the ratio of another like past due so it is good it is mean the Prosper don't take a risk and 
nothing is bad


10- the most loan amout is less than 10000 and its monthly loan is less than 500

11- the most loans are less risk 

12- 2013 was the year the biggest loans happened (375740433)

13- 2013 was the year the biggest monthly loan payments happened (11571616.60)

14- the most common risk ratio with all occupation  is c except (Executive & computer programer (A) )

15- doctor occupation that is the most average income monthly , and students are the least income

16- relationship between loan amount & trades  (the common less than 10,000 dollar and less than 100 trades )

17- relationship between loan amount & investors (the common between 10,000 - 25,000 dollar and between 0 - 600 investors)

18- investors in last years in Currently In Group

19- total trades were bigger at last years   not in the group 

20 -we can see the some of reasons loan is beginning at last 4 years (2011-1014) like (Motorcycle ,Vacation ,Household Expenses, Medical/Dental,Engagement Ring ,Taxes, Baby&Adoption, Green Loans ,Large Purchases )

and we can see the some of reasons loan is beginning at last 3 years (2012-2014) like (Boat, RV)

21- the investors and total trades diffuse between 0-600 investors & 0 -80 total trades in last years 

22- 
>1- term 60 months had the biggest loan amount and not have hr risk

>2- 36 months had an average loan amount and have hr risk

> 3- 12 months had a less loan amount and not have hr risk


## Key Insights for Presentation

> For the presentation, I just focus on features that relate with the loan amount and reasons for loan and the occupation how this effect  every year  for  the loan .