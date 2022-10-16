# Amazon_Vine_Analysis
## Overview
Analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

There are 50 datasets and each one contains reviews of a specific product, from clothing apparel to wireless products. In this project one of these datasets were chosen and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, PySpark was used to determine if there were any bias toward favorable reviews from Vine members in the dataset. 

## Results 
- There are 647 paid reviews.
- There are 229 paid 5 star reviews.
- 35.39% of the paid reviews were 5 star.
<img width="467" alt="Screen Shot 2022-10-15 at 10 18 47 PM" src="https://user-images.githubusercontent.com/105958160/196014925-11514cee-2aed-427f-9e4a-a9f495cd948b.png">

- There are 74,113 unpaid reviews.
- There are 43,217 unpaid 5 star reviews.
- 58.31% of the unpaid reviews were 5 star.
<img width="581" alt="Screen Shot 2022-10-15 at 10 18 58 PM" src="https://user-images.githubusercontent.com/105958160/196014926-1cad6fbc-a7df-4ed6-9df0-affbffdc51e7.png">


## Summary
I don't detect any bias in these findings for Vine program assessments. 58.31% of the positive reviews weren't from Vine where 35.39% were. 
