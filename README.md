# Amazon_Vine_Analysis

## Analysis Overview

Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

### This new assignment consists of two technical analysis deliverables and a written report. You will submit the following:

- Deliverable 1: Perform ETL on Amazon Product Reviews
- Deliverable 2: Determine Bias of Vine Reviews
- Deliverable 3: A Written Report on the Analysis (README.md)

## Results

### How many Vine reviews and non-Vine reviews were there?

#### Vine Reviews
- 33 - paid
- 45,388 - unpaid

![Resources/paid reviews.png](https://github.com/lesliemayeux/Amazon_Vine_Analysis/blob/8c1ecd80dbd5b9f529dca150641370dfbc2c1bf0/Resources/paid%20reviews.png)
![Resources/unpaid reviews.png](https://github.com/lesliemayeux/Amazon_Vine_Analysis/blob/8c1ecd80dbd5b9f529dca150641370dfbc2c1bf0/Resources/unpaid%20reviews.png)

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

#### 5 Star Reviews
- 15 - paid
- 23733 - unpaid

![Resources/paid 5 star.png](https://github.com/lesliemayeux/Amazon_Vine_Analysis/blob/fc563386508a86e921c8d784346b83e7319446a7/Resources/paid%205%20star.png)
![Resources/unpaid 5 star.png](https://github.com/lesliemayeux/Amazon_Vine_Analysis/blob/fc563386508a86e921c8d784346b83e7319446a7/Resources/unpaid%205%20star.png)

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

#### Percent of 5 Star Reviews
- 45.45% - paid
- 52.29% - unpaid
![Resources/percent paid.png](https://github.com/lesliemayeux/Amazon_Vine_Analysis/blob/a917b5202aa46d5bf96e00fd880d86d4deec3a65/Resources/percent%20paid.png)
![Resources/percent unpaid.png](https://github.com/lesliemayeux/Amazon_Vine_Analysis/blob/a917b5202aa46d5bf96e00fd880d86d4deec3a65/Resources/percent%20unpaid.png)


## Summary

From my analysis, there are n ot any bias' for reviews.  In fact, I do not think the Vine program was worth it as the unpaid reviews had a higher 5-star percentage. I would probably recommend not doing the program for apparel. 

