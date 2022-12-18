# Amazon_Vine_Analysis

## Overview of the Analysis

The purpose of the project was analyzing Amazon reviews written by members of the paid Amazon Vine program.

## Results of the Analysis

In the first deliverable, one dataset was picked among a list of 50 datasets, an ETL process was performed to extract the 
dataset, transform the data, sonnect to an AWS RDS instance, and load the transformed data into pgAdmin by using PySpark.
By using the data from challenge_schema.sql file, a new query was run in PgAdmin, and four tables were created in database.
After creating the tables, each one was transformed into some DataFrames by using the required functions as instructed. 
Connection with AWS RDS instance was made, and DataFrames were loaded in PgAdmin.
In the second deliverable, the data was filtered as stated in challenge instructions by using Pandas. 

- There were 1741095 vine reviews in total, 31545 of this amount was non-Vine, and 285 were Vine rewiews.
- The number of 5-star reviews in total was 1113563
- The percentage of 5-star reviews for the two types of review were 77.61 % for Vine; and 17.33 % for non-Vine.

## Summary of the Analysis

According to the analysis, the total number of reviews was 1741095, and among these 1113563 were 5-star reviews, which means
approximately 64% of the total reviews were 5-star reviews, which can be considered as a non-positivity bias. Among these
5-star reviews, 77.61 % were for Vine; and 17.33 % were non-Vine. Vine program is the paid program in the system, which the
users are registered and not boot accounts. The fact that the percentage of Vine accounts with 5-star reviews was the majority
percentage of the total can make the result of the analysis more accountable. 
