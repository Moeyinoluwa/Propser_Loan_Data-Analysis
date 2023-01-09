# Propser Loan Dataset Exploration
## by Moyinoluwa Sobowale

## Dataset
> The dataset being used for this project is the Prosper loan Dataset provided by Udacity containing information of 113,937 loans with 81 variables(columns) on each loan. [Find column details here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).

> The dataset columns are divided into two main categories:
>- Borrower's features
>- Loan features

> Out of 81 loan features, I selected 20 columns and stored them in a dataframe called 'loan' for my analysis including 5 major columns of interest which are:'BorrowerAPR', 'BorrowerRate', 'LoanOriginalAmount', 'LoanOriginalDate', 'Term'.
> The loan dataframe was wrangled to achieve proper data visulization.


## Summary of Findings

> A key insight during the univariate analysis was understanding the fact that home ownership distribution was almost evenly distributed, meaning home ownership did not have a significant effect on getting a loan from Prosper. After researching the two letter state abbrevations on wikipedia Resource from wikipedia and transforming the 'BorrowerState' column, it was interesting to know that Carlifonia is the state with the highest number of borrowers and North Dakota is the state with the least number of borrowers. I also discovered that majority of the borrowers (almost 70000) are employed and they have an income range of 25,000 - 74,999 dollars. Another insightful information was the fact that majority of the loans were collected in 2013 and no loan was taken in 2005, this was very strange to me. Was Prosper out of operations in 2005? I think this is an important insight to investigate further.
> Investigating further during my bivariate analysis, I discovered that Borrowers with full time employment status tend to take loans with term duration of 36months. Employed borrowers tend to take loans with 36months duration. This is interesting to me as i would assume that they have a stable monthly source of income i.e their salary. I also discovered that majority of the employed borrowers are homeowners
> The multivariate analysis reavealed that verifiable income has an effect on the original loan amount disbursed to a borrower. Borrowers who earn 100,000+ dollars and have verified their income tend to get larger loan original amount than those whose income are not verifiable. The borrower rate and borrower APR a have strong positive correlation meaning that they are directly proportional i.e the rise in one vale leads to the rise in the other. Also, the Loan original amount has a weak correlation with the borrowers rate and borrower APR.
> Generally, the borrower's APR and having verifiable income seem to be crucial when giving out loans to borrowers.


## Key Insights for Presentation

> For the presentation, my goal is to explore my features of interest to discover the relationship between the borrowers and the loans disbursed to them. Following that, I will introduce my features of interest, followed by how each feature relates to one another and finally, how their correlation is affected by other variables. 