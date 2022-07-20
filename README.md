# prosper-loan-data


## Dataset

Prosper is an online peer-to-peer lending marketplace where credit worthy borrowers can request loans and investors can invest in portions of each loan.

After a borrower accepts the investors loan offer, the application information is verified and investors have up to 14 days to commit funds to the loan through their prosper account.

Once a borrower passes any additional verification requirements and one or more investor(s) commit enough funds to the loan, then it is ready for origination.

Borrowers make fixed monthly loan payments throughout the duration of their 3 - 5 year term. The payments are comprised of principal, interest and any other applicable fees where the investors receive a portion of those payments that are proportional to the share of the loan. These funds are deposited directly into their investor's prosper accounts.


## Summary of Findings

1. The dataset had some duplicated rows which I removed.
2. The distribution of investors is skewed to the right with a large group of number of investors on the left while there's few of them on the right. On plotting the Investors column on a log scale, the distribution is bi-modal, with most of the listings having only one investor in the dataset. The other investors who invested averaged at about 106.
3. A large number of borrowers were those who had a prosper rating of A, B, C and D with the least number of borrowers had a prosper rating of AA with those who had a prosper rating of C being the majority of the lot.
4. Majority of the borrowers in the dataset had an on-going while quite a significant number of about 4000 borrowers had their loan payments completed. 4.96% of the loan borrowers had defaulted on their loan payments.
5. Most of the borrowers income ranged from 25,000 - 74,999 US dollars with a majority of those being those who had an income of between 25,000 - 49,999 US dollars. No borrowers had an income of 0 US dollars while those who were not employed were the least in the dataset at 0.72%.
6. Majority of the borrowers in the dataset had a numeric prosper rating of 4, 6 and 8 while the majority among them were those with a prosper rating of 4. Borrowers who had a prosper rating of 1 were the least in the dataset.
7. A majority of the loan borrowers made monthly payments of 160 US dollars. Most borrowers in the dataset are those who made monthly loan payments of less than 500 US dollars.
8. Most people in the dataset are those who had a debt to income ratio of less than 1. Borrowers who had a debt to income ratio of above 10 were less than 300 in the dataset.
9. Majority of the borrowers in the dataset had their source(s) of income verified while those with unverified source(s) of income were just about 7.59%.
10. There was a very close range between borrowers who had a home ownership and those who owned no homes with those who had a home ownership being the majority.
11. Most borrowers in the dataset had an original loan amount of about 4000 - 4500 US dollars. The least amount of loan requestes was 1000 US dollars.
12. Majority of the borrowers had less than 12 months to their count since receiving the loans they were lent. No borrower had loan lent to him or her between the 58 and 64 mark while quite a significant number of borrowers had more than 65 months to their count.
13. Majority of the borrowers in the dataset had stated less than 10000 US dollars as their monthly income. 91 borrowers in the dataset had more than 50000 US dollars stated as their monthly income while only 2 people in the dataset had stated more than 500,000 US dollars as their monthly income with the highest being a 1.75 million US dollars.
14. A heatmap was plottes showing the correlations between some numeric variables. Of the given numeric variable, only those between the monthly loan payments and loan original amount showed a strong correlation. All other numeric variables showed a weak correlation. That is further supported by the pair grid plotted.
15. Most of the borrowers in the dataset had only one investor lending them money for the majority of the datasets income range.
16. For borrowers who stated their monthly income as 0 had a range of 0 to about 500 investors loan them money. Of those borrowers, a majority of them had less than 200 investors loan them money. The number of investors seems to be increasing with an increasing number of the stated monthly income with the peak being at about 10,000. Even then, only a few of those borrowers had more than 600 investors loan them money.
17. The number of investors lending borrowers loans increased as the number of the borrower's original loan amount increased.
18. Majority of the borrowers with an alpha prosper rating of A, B, C and D had only one investor lending them money.
19. For the numeric prosper score ratings, most of the borrowers received loans from less than 200 investors and that an increase in the number of investors increased with an increase in the prosper rating score. Borrowers with a prosper rating of 10 had the most number of investors.
20. The borrower with the most number of investors had 51 months since his / her loan origination. For borrowers with more than 65 months since their loan origination, the number of investors decreased with an increase in the number of months.
21. Majority of the outliers in the number of investors lay on those borrowers who owned homes. They also had the highest interquartile range.
22. Majority of the borrowers who made payments of about less  $1250  a month had at least one investor. Quite a significant number of borrowers had at least one investor yet they made no monthly payments.
23. Borrowers who had completed their loan payments had the most number of outliers and the highest median followed closely by those who had defaulted.
24. Most borrowers who had their source(s) of income verified had the most outliers in terms of number of investors.
25. Borrowers with a small debt to income ratio had the most number of investors as compared to those with a low debt to income ratio.
26. For borrowers who had an alpha prosper rating of AA, A, B and C, a majority of them owned homes while those with a lower prosper rating had those who did not own homes as the majority.
27. Of borrowers who had their source(s) of income verified and made monthly loan payments of less than 600 US dollars, a majority of them had less than 400 investors lending them money.
28. In all the numeric prosper rating, borrowers who did not own homes had a few number of investors lending them money.
29. In the state with the most number of borrowers, an increase in the number of investors and an increase in the loan original amount resulted to a higher monthly loan payments being made by the borrowers.

## Key Insights for Presentation

Here are the key insights in my slide show:

1. Most of the borrowers had an alpha prosper rating of C while the least had an alpha prosper rating of AA. Majority of the borrowers lay between the ratings of A, B, C and D.
2. Majority of the borrowers had stated their stated monthly income as about 4000 to 4500 US dollars. There were about 91 borrowers who stated their monthly income above 50000 US dollars while only 2 borrowers states their monthly income above 500000 US dollars and the highest borrower stating a monthly income of around 1,750,000 US dollars.
3. An increase in the number of the loans original amount seemed to have increased the number of investors lending borrowers loans.
4. Most investors lent their money to borrowers who had their source(s) of income verified throughout the dataset. Also, for borrowers who could do a monthly loan payment of more than $1750 all had their source(s) of income verified.
5. The number of investors in the state with the most number of borrowers increases with an increase in the number of loan original amount. The amount of monthly loan payments seems to have been increasing with an increase in the loan original amount as well as an increase in the number of investors.
