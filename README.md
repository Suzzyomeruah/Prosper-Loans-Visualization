# Prosper-Loans-Visualization

# (What are the Factors that Affect Loan Outcome?)
## by (your name here)


## Dataset

> Prosper is a lending platform in the U.S. that offers a variety of resources people can use to try and improve their financial health, regardless of their financial situation. Users can consolidate debt, improve their home, or finance healthcare costs with personal loans among many other purposes. Investors who may be looking for new opportunities to diversify their portfolio can invest in personal loans.

>This data set contains 113,937 loans with 81 variables on each loan, with duration between november 2005 to march 2014, including loan amount, borrower rate (or interest rate), current loan status and borrower income. 

> I started by exploring the distrubution of the various variables including the main variables of interest which include distribution of Loan amount, Listing Category, Term, Loan status, borrower rate and lender yield.

I looked at some borrower characteristics which are Borrower state, employment status, Income range, prosper rating and homeowners. I also viewed the distribution of investors, monthly loan payments and amount delinquent.

Some of the charts(Investors, MonthlyLoanPayments and AmountDelinquent) were not informative at first hence I visualized on a log-scale for a more detailed look.

Next I created a heatmap and plot matrix to visualize numerical variables before proceeding to check for the relationship between various variables

In the Multivariate section, I visualized how a combination of some of the main variables (Loan Amount, Borrower rate and Loan status) interacted with other variables like Prosper rating, Term, Income range,



## Summary of Findings

- Average loan amount is about 5000 dollars and there are relatively more loans with lower amounts and fewer loans with higher amounts, also average borrower rate is 0.2

Majority of the borrowers come from California(CA), they're employed, earn between 25,000 to 74,000 dollars, have a 'C' Prosper rating and often own a house

LoanOriginalAmount and BorrowerRate are negatively correlated which suggests that larger loans have lower borrower rate compared to lesser loans

Strong positive correlations between Lender yield and Borrower Rate which is logical, higher borrower rates should result in higher lender yield

Strong negative correlation between Prosper rating and borrower rate, which suggests that high prosper ratings have lower borrower rates

Loan amounts increased over the years with january recording the most loans while borrower rates dropped over the years

Lower borrower rates are associated with higher completion rates, while higher borrower rates are associated with higher rates of default, charge off, and past due status
Borrower rates are highest for HR(High risk) Prosper rating and lowest for the highest Prosper rating AA.
This shows that borrowers with better Prosper rating get lower rates

Loans for Auto, Business, Large purchases, Medical/dental and RV may be riskier than other purposes like debt consolidation and student use. Loans taken for debt consolidation are most likely to be completed

We can see that prosper ratings of 4 (same as C- rating) and above have the largest Loan amounts but lowest borrower rates

Borrowers in higher income ranges tend to have lower rates across all loan statuses, with the lowest rates concentrated in the $100,000+ income range

Prosper tends to give larger loans to individuals with higher incomes and the 60-month term is the most popular among borrowers



## Key Insights for Presentation

> The loan original Amount is multimodal with loan amount of about 5000 having the most peak
The chart suggests that there are relatively more loans with lower amounts and fewer loans with higher amounts

> 2011 has the highest number of completed loans when Loan status is compared over time

> Loans taken for debt consolidation are most likely to be completed

> Prosper ratings of 4 (same as C- rating) and above have the largest Loan amounts but lowest borrower rates

> Borrowers in higher income ranges tend to have lower rates across all loan statuses
Loans that are charged off or defaulted tend to have higher rates across all income ranges, while completed loans tend to have the lowest rates

> The median borrower rate is generally higher for loans that have defaulted or charged off compared to loans that are current or completed
The median borrower rate tends to increase as the loan term gets longer, with the 60-month term having the highest median rate.

