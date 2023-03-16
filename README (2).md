# Amazon Vine Analysis

### Overview

This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.

## Resources
- Data Source : Amazon Review Dataset
- Software : AWS, PostgreSQL

## Results
- Where vine program is active : 42% are 5 Star Reviews
- Where vine program is inactive : 46% are 5 Star Reviews
![image.png](attachment:image.png)

- Total number of reviews (Paid) : 1080
- Total number of reviews (Unpaid) : 49659
- Total number of 5 Star reviews (Paid) : 454
- Total number of 5 Star reviews (Unpaid) : 23034

## Summary
42% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is 46%. This does not describes a positivity bias for reviews in the Vine program. Additionally, we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
