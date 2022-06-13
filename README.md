# Challenge 16
Sied H Mohamed

# Overview of the project 
The purpose of this project is to analyses the reviews rewritten by Amazon paid Vine program and non-vine(unpaid) shoes buyers. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. I also used PySpark, to determine if there is any bias toward favorable reviews from Vine members in your dataset. 

# Results
## Extracted data frame

## Data loaded to PgAdmin

## Paid Vine program and Unpaid program

# Paid reviews
-	Total Reviews: 22
-	Number of 5 star reviews:13
-	Percentage of  5 star reviews:59.09%
# Unpaid reviews
-	Total Reviews:26971
-	Number of 5 star reviews:14475
-	Percentage of  5 star reviews:53.67%

# Summary
The extent of bias due to the payment program the difference between percentage of  5 star reviews of the paid and unpaid programs. 
- Bais= Paid percentage of  5 star reviews-Unpaid percentage of  5 star reviews=59.09%-53.67%=5.42%
- The 5-star reviews of paid program is higher than the unpaid 5 star revies by 5.42%. 
- It is very difficult to make a cuasl claim that payment program lead to higher number of 5 star reviews. There should be a more statistical analysis to reach at the conclusion. However, the result shows that the payment program is assocaited with higher number if reviews. 
This may or may not be attributed to the payment program. 

