# Amazon_Vine_Analysis

## Overview of the Analysis

Utilizing our knowledge of Amazon AWS and google colab, the purpose of this assignment was to analyze Amazon reviews written by members of the paid Amazon Vine program.  Amazon Vine allows various manufacturers and publishers to receive reviews for their products.  

For this assignment, we were provided access to 50 datasets.  Each dataset featured reviews for a certain product.  After choosing a dataset, we utilized pyspark to perform the ETL process (extracting data, transforming data, connecting to Amazon AWS RDS service, and loading the transformed data into pgAdmin).  Finally, we used pyspark to determine if there was any bias toward favorable reviews from the chosen dataset.

## Results

How many Vine reviews and non-Vine reviews were there?

There were 416 total paid vine reviews and 86356 total non-paid vine reviews.
[GitHub Picture]()

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There were 172 5-Star paid reviews and 45472 5-Star non-paid reviews.
[GitHub Picture]()

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

The precentage of paid 5-Star reviews was 41 percent, and the percentage of non-paid 5-Star reviews was 53.
[GitHub Picture]()

## Summary

Based on the percentage of paid 5-Star and non-paid 5-Star Amazon Vine reviews (41% and 53%), I would say that there is a slight bias towards 5-Star reviews for both paid Amazon Vine reviews and non-paid Amazon Vine reviews.  I say this because the review program has 1-Star, 2-Star, 3-Star, 4-Star, and 5-Star review options avaliable, but roughly 4 out of every 10 paid reviews were 5-Star while roughly 5 out of every 10 non-paid reviews were 5-Star.  This leads me to believe that there was indeed a 5-Star review bias.
