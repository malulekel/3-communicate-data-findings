# Prosper dataset 

#### communicate-data-findings

Introduction

This data set contains 113,937 loans with 81 variables on each loan,  including loan amount, borrower rate (or interest rate), current loan  status, borrower income, borrower employment status, borrower credit  history, and the latest payment information.
 
### Summary of findings 

The main purposes of this project are to summarize the characteristics of  variables that can affect the loan status and to get some ideas about the  relationships among multiple variables using summary statistics and data  visualizations.

In the exploration the following has been shown:  

- Observing the employment status data the the borrower who are employed and who work full-time have a higer rating than others meaning employment does play a major role when it comes to a loan status being approved and it does play important factor.

- In the a-axis the heatmap represent term and in the y-axis it represent EmploymentStatus.When you observe this heatmap uses color to represent the extent of the mean loan amount and the higher values are darker shades of green. In the cells of a heatmap the amounts in it show the mean loan amount for that specific category.

Analysing the data I can see that the heatmap reveals that customers who are employedor full-time employed tend to have higher loans for longer loan terms while customers are not employed or have other employment statuses tend to have a smaller loan not in a longer term.So yes employment have an impact to both variables.

- It has come to light that the employment and Rating is showing the distribution of ProsperRating (Alpha) for each value of EmploymentStatus. We can see that for most EmploymentStatus categories, the majority of loans have a ProsperRating of C or D. However, there are some differences between categories: for example, self-employed borrowers are more likely to have a ProsperRating of HR (high-risk) than borrowers who are employed or retired.

-From the bar graph people who are employed are in high numbers compared to a person who is not employed, retired or works part-time and the rest of the employment status.Status which is showing full-time and self employes is showing a higher rating meaning employment does 
play a major role when it comes to a loan status being approved.

- The debt to income ratio and Borrower APR the plot show a relation between the two variables, when one increase the other also increase. This suggest that borrowers with a higher DebtToIncomeRatio the more likely to get higher APR.

- Prosper Score: The Prosper Score is a proprietary scoring system that assesses the risk of a loan. The rating from D-A is a good rating tand the outcome is showing with the ones who are getting the loan compared to other bad ratings.

### Key insights 

- The relationship between the rating and in ratio debt income ratio is lower. 

What effects the borrowers APR or interest rate in prosper loan ?

The borrower's APR or interest rate in a Prosper loan is determined by a number of factors, including their credit score, debt-to-income ratio, loan amount, loan purpose, and loan term. Additionally, Prosper takes into account the borrower's past payment history, the amount of available funds in the borrower's account, and the borrower's listing category even though not all of the variables are not covered most of the them are analysed. 