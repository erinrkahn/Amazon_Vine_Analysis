# Amazon Vine Analysis

## Overview of the Analysis 

### Purpose

The purpose of this analysis is to look at The Amazon Vine program for a specific product type where manufacturers and publishers can receive reviews for their products. In order to perform this analysis, PySpark was used to perform the ETL proces on a Amazon Review data on healthcare products. Analyses were performed to determine if there is any bias towards favorable reviews from Vine Members. 

## Results

-**How many Vine reviews and non-Vine reviews were there?**
###### Vine Reviews
> ![vine_reviews](https://user-images.githubusercontent.com/77405273/119279470-d37a2d00-bbe0-11eb-99e0-6661b4ffa1c3.png)
###### non-Vine Reviews
> ![nonvine_reviews](https://user-images.githubusercontent.com/77405273/119279471-d543f080-bbe0-11eb-9cf0-5e6be0609309.png)

There were 497 Vine reviews for this subset of healthcare products and 120,863 non-Vine reviews.

-**How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**
###### 5 Star Reviews
> ![five_star](https://user-images.githubusercontent.com/77405273/119279473-d6751d80-bbe0-11eb-9346-3dc1f669e8c9.png)

There were 220 Vine reviews and 74,470 non-Vine reviews.

-**What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?**
###### Vine 5 Star Reviews
>![paid_five](https://user-images.githubusercontent.com/77405273/119279474-d70db400-bbe0-11eb-90cf-26c39afecc9e.png)
###### non-Vine 5 Star Reviews
> ![unpaid_five](https://user-images.githubusercontent.com/77405273/119279475-d70db400-bbe0-11eb-8156-3c432b56307c.png)

44% of Vine reviews were 5 stars, while 62% of non-Vine reviews were 5 stars.

## Summary

