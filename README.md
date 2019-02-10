## Dataset
This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

## Summary of Findings

### Univariate Analysis
In the beggining of univariate exploration, I've found that majority of the loans were 36 term loans and very small amount of 12 terms. From there on, I've calculated distribution of credit scores using histogram, I've found that majority of credit scores fell in between 500 and mid 800's. Using histogram again on original loan amounts, it appears that majority of the loans original amount was in-between a 1000 to 15000, with small amount going up to 35000. 

### Bivariate Analysis
Moving on to Bivariate analysis, I've used violin plot to determine the distribution of original loan amounts between terms, the violin plot shows that the lower the term the lower the original loan amount. Using the violin plot again, I've calculated the distribution of interest rates on each term. Majority of high interest rates fell in the 60 terms while majority of low interest rates fell 12 terms. On the third plot, I've used a boxplot to determine each employment status original loan amount and borrow rate. Self-employed and Employed had the highest amount of original loans while also having one of the lowest amount of interest rates. From there on, I've used scatter plot to measure many variables against interest rate such as debt-to-income ratio, total inquiries, employment duration, and deliquincies. The ones that stood out the most was high credit scores had most effect on getting low interest rates, as well as having low deliquincies and low debt-to-income ratios.

### Multivariate Analysis
As for multivariate analysis, I've focused on two variables, credit scores and interest rates and looked into wether homeownership, terms, or employment status had any effect on them. Starting off with the one that had the least effect was homeownership, wether you were a homeowner or not did not change the borrow rate for the same credit score. For the terms, the lower the term was the lower the interest rate for the same credit score. Finally, being employed showed a significant enough reduction in borrow rates as opposed to those not-employed in some form.

## Insights for presentation
On the presentation, I've focused greatly on how effective the plots will communicate the messasge. The slides are failrly simple, there will be a title for it as well as short description so you can get a clear idea of what you're walking into. My slides are in html format from Jupyter Notebooks slides. So to navigate keep pressing right arrow on bottom right and when bottom arrows becomes clickable, you'll be able to view plot for that specific topic.