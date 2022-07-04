# Amazon_Vine_Analysis

## Overview of Project

### Purpose

The purpose of this project was to analyze one of fifty datasets containing amazon product reviews to determine if the Amazon Vine program generates biased reviews. We will do this by using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.

## Results

### Number of Total Reviews

  •	Number of Vine reviews 

![total_paid_reviews.png](https://github.com/SZapata4/Amazon_Vine_Analysis/blob/main/Resources/total_paid_reviews.png)

  •	Number of non-Vine reviews

![total_unpaid_reviews.png](https://github.com/SZapata4/Amazon_Vine_Analysis/blob/main/Resources/total_unpaid_reviews.png)


### Number of 5 Star Reviews

  •	Number of 5-star Vine reviews

![paid_5_star_reviews.png](https://github.com/SZapata4/Amazon_Vine_Analysis/blob/main/Resources/paid_5_star_reviews.png)

  •	Number of 5-star non-Vine reviews

![unpaid_5_star_reviews.png](https://github.com/SZapata4/Amazon_Vine_Analysis/blob/main/Resources/unpaid_5_stars_reviews.png)

### Percentage of 5-Star Reviews

  •	Percentage of 5-star Vine reviews

![paid_5_star_percent.png](https://github.com/SZapata4/Amazon_Vine_Analysis/blob/main/Resources/paid_5_star_percent.png)

  •	Percentage of 5-star non-Vine reviews

![unpaid_5_star_percent.png](https://github.com/SZapata4/Amazon_Vine_Analysis/blob/main/Resources/upaid_5_star_percent.png)

## Summary

Looking at the numbers above Vine reviews are approximately 41.6% 5-star reviews whereas the non-Vine reviews are approximately 53% 5-star reviews. This leads me to believe that there is no positivity biased for Vine program reviews. To get a more precise read on this I think I would expand my analysis by adding 4-star reviews as positive reviews. This would increase our sample size and would give us more accurate percentages. 

