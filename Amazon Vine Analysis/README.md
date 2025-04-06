# Amazon Vine Analysis

## Overview of the analysis:
The main objective of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. For this analysis, we used the power of big data to translate the reviews to analyze the data. We used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We also used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. 

## Resource:

* PySpark, AWS -RDS and S3, SQL and PgAdmin4, Google Colab Notebook

## Results:

#### Number of Vine reviews and non-Vine reviews:
* The total number of paid or Vine reviews was 618. On the other hand, the total number of unpaid/non-Vine reviews were 71,969 which is a every hign number compared to the vine review. Result also shown below.

![image](https://user-images.githubusercontent.com/114262970/218235837-3312fd2b-72f1-4770-96e7-af9fa59cd63a.png)

#### Number of Vine reviews and non-Vine reviews with 5 stars Rating:
* Among the 618 Vine reviews, 223 reviews had a 5 star rating. However, 31390 non_vine reviews received a 5 star rating.

![image](https://user-images.githubusercontent.com/114262970/218236229-8a55686f-9a45-4b8a-b1c1-a3133b145b76.png)

#### Percentage of Vine reviews and non-Vine reviews with  5 stars Rating:
* The 5 star rating percentage for paid/Vine-reviews is 36.1% compared to non_vine review with a percentage rate of 43.6%. 

![image](https://user-images.githubusercontent.com/114262970/218237939-a4c9de44-8bc9-4dca-b009-5364e92b4722.png)

## Summary: 
In conclusion,after reviewing the abovementioned result, there is not any positivity bias for reviews in the Vine program. Both programs received a closer 5 star percentage rate. No significance difference in 5 star percentage rating for both programs. 
Recommendation: One additional analysis I would like recommended to include in the analysis, comparing the helpful_votes for the Vine and Non-vine program. Shown below. This will give us a different perspective to support our finding. 

![image](https://user-images.githubusercontent.com/114262970/218240360-9142edfa-ef40-4216-85da-b2032fd06dcc.png)
