# Prosper dataset 

#### communicate-data-findings

Introduction

This data set contains 113,937 loans with 81 variables on each loan,  including loan amount, borrower rate (or interest rate), current loan  status, borrower income, borrower employment status, borrower credit  history, and the latest payment information.
 
### Summary of findings 

The main purposes of this project are to summarize the characteristics of  variables that can affect the loan status and to get some ideas about the  relationships among multiple variables using summary statistics and data  visualizations.

In the exploration the following has been shown:  

- Loan Term: The length of time a borrower has to repay a loan affects the outcome of the loan. Longer loan terms may provide more flexibility for the borrower, but may also increase their risk of defaulting.This will be compared to another factor in bivariate so we can come to a conclusion on how it affects repayment etc.

-Customers who have a credit grade of C, D and B have a higher chance of getting a loan whereas NC has a lower chance of getting a loan.A higher creditscore  indicate a lower risk of default and, therefore, a higher likelihood of loan approval.

-From the bar graph people who are employed are in high numbers compared to a person who is not employed, retired or works part-time and the rest of the employment status.Status which is showing full-time and self employes is showing a higher rating meaning employment does 
play a major role when it comes to a loan status being approved.

-This graph shows a PairGrid plot with multiple variables from the Prosper loan dataset. The variables used in this plot are DebtToIncomeRatio, ProsperRating (Alpha), and Term. The upper triangle of the grid contains scatterplots showing the relationship between the variables, while the diagonal contains histograms showing the distribution of each variable. The lower triangle contains violin plots, which are similar to box plots but show the distribution of data in a more detailed way.

From the scatterplots, we can see that DebtToIncomeRatio and ProsperRating (Alpha) are weakly negatively correlated, meaning that as the debt-to-income ratio increases, the Prosper rating tends to decrease slightly. The scatterplot of ProsperRating (Alpha) and Term shows that longer-term oans tend to have higher ratings, while shorter-term loans tend to have lower ratings.

The histograms show that DebtToIncomeRatio is slightly skewed to the right, indicating that most borrowers have a relatively low debt-to-income ratio. ProsperRating (Alpha) is roughly normally distributed, with a peak in the B rating category. The histogram for Term shows that the most common loan term is 36 months.

The violin plots in the lower triangle show the distribution of each variable. The DebtToIncomeRatio plot is skewed to the right, with a few borrowers having very high ratios. The ProsperRating (Alpha) plot shows that the distribution is wider in the lower rating categories, indicating that there is more variability in borrower characteristics among those with lower ratings. Finally, the Term plot shows that the 36-month term is the most common, with a few borrowers taking out loans for longer or shorter terms.  


### Key insights 

- The relationship between the rating and in ratio debt income ratio is lower. 

What effects the borrowers APR or interest rate in prosper loan ?

The borrower's APR or interest rate in a Prosper loan is determined by a number of factors, including their credit score, debt-to-income ratio, loan amount, loan purpose, and loan term. Additionally, Prosper takes into account the borrower's past payment history, the amount of available funds in the borrower's account, and the borrower's listing category even though not all of the variables are not covered most of the them are analysed. 