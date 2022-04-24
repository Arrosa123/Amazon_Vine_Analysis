# Amazon_Vine_Analysis
## Overview of the analysis of the Vine program:

The purpose of this project was analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.
Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
In this project, we have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. Then we picked one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. 
Next, used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. At the end, we wrote a summary of the analysis to submit to the SellBy stakeholders.

## Results:

WE got 
### - How many Vine reviews and non-Vine reviews were there?

- 969 reviews were from Amazon Vine members
- 43,745 reviews were not from Amazon Vine members


![2022-04-23](https://user-images.githubusercontent.com/96403349/164958893-6d6828a1-a67b-4310-a3eb-f163429ecd1a.png)

### - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- 430 5 stars reviews from Vine members
- 19233 5 starts reviews from non-Vine members

![2022-04-23 (1)](https://user-images.githubusercontent.com/96403349/164959147-74707b1d-ba3f-45c9-b65d-a97568fda0fc.png)

### - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- 44.4% of reviews by Amazon Vine members were 5 stars
- 43.9% of reviews not by Amazon Vine members were 5 stars

![2022-04-23 (2)](https://user-images.githubusercontent.com/96403349/164959317-c73c46ce-8931-4e73-a9d2-36f64f434cd7.png)

## Summary:

- By comparing the percentage of reviews 5 stars from both Amazon Vine members and Amazon non-Vine members, we can concluded that there is no positivity bias for reviews. 
- Also the percentages of 5 stars reviews of both groups are almost same.
- To get a better analysis of the positivity bias on the Vine program, it is recommended to perform the same analysis on the lower than 5 stars reviews. 



