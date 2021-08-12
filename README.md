>Summary of Findings
>
>This data visualization project explores the Prosper Loan data set containing borrowers loan data and attributes for approximately 11,4000 listings.

> Univariate Exploration
> 
> The borrowers rate distribution showed that maximum number of borrowers received an interest rate of 0.14-0.16. Here we see there are some outliers for interest rate below 0.04 and above 0.36. These were removed. Credit score distribution shows that largest loans are given to people with 600-800 credit score rating. Here we see that the 0 bin size may not be useful, as these are credit scores that are probably unavailable, so they are dropped. Employment status distribution shows that Employed people have the largest loans, followed by full-time and self-employed. However Part-time, not employed, and retired have the lowest number of loans. Regarding Number of Days deliquent, the log scale plot of borrowers and the number of days delinquent shows a multimodal chart for LoanCurrentDaysDelinquent, with the max borrowers were about 2000 days deliquent, and another at 250 and 500 days deliquent. The histogram of Listing Category_num shows that ListingCategory_num of 1=Debt Consolidation, was the most common reason for loans. 
>  
>   
> Bivariate Exploration 
>   
>The correlation coefficient chart for borrower interest rate and credit score shows a moderate negative linear relationship between Borrower Rate and CreditScore. The correlation coeffecient of 0.288 between LoanCurrentDays Delinquent and creditscore shows a weak negative relationship between the two. There was not much relationship established between borrower rate and loan currentdays delinquent. This scatter plot matrix chart shows a moderate negative linear relationship between Borrower Rate and CreditScore. Comparing the employment status against the 3 numeric variables shows that variability of the borrower rate is quite similar regardless of Employment status. The employment status shows that retired borrowers have the most days delinquent compared to employed, full time and self-employed borrowers. Regarding the credit score, the part-time employees had a lower credit score, and smaller range of credit score than the other borrowers. The strip plot shows that Employed borrowers had a higher credit score vs the partitime and Not employed. 
The pair grid shows that the employed had less days delinquent than the retired, part-time and not employed. The borrower rate was quite similar for all the employment levels.
>     
>  Multivariate Exploration
>  
>The multivariate plot above shows that the full-time borrowers with Green loans and Motorcyle have the lowest rate, vs the un-employed with wedding loans and green loans and full time borrowers with engagement ring loans had the highest rate.  Overall the fulltime and employed see to have the lower interest rates compared to the un-employed, regardless of the the listing category. The plot shows that Self-employed borrowers, with debt consolidation loan and retired borrowers with debt consolidation loan had the highest number of delinquent days. Also full time borrowers with engagement ring loan had the lowest credit score while borrowers with green loans had the highest credit score.
   
> Key Insights from the Data 
> 
>We observed various relationships between the variables.  Overall the fulltime and employed borrowers seem to have the lower interest rates compared to the un-employed, regardless of the the listing category. As we expected, better credit score and a better employment status meant better interest rate. Further we see the type of loan affects the rate of interest rate.It was interesting to find that the type of loan (engagment ring loan) had a high interest rate regardless for full time borrowers. 
