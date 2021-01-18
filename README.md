# Amazon_Vine_Analyis

## Overview
To analyze Amazon reviews written by members of the paid Amazon Vine program.  The Amazon Vine program is a service that allows manufacturers and publishers to recieve reviews for their products.
### Purpose
Pick one of 50 datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.  Use PySpark, Pandas, or SQL to determine if thereis any bias toward favorable reviews from Vine members in the dataset.  Write a summary of the analyis.
### Resources
- Data Source: amazon_reviews_us_Video_Games_v1_00.tsv.gz
- Software, apps, libraries:
  - Python 3.6.1
  - Pandas
  - pgAdmin
  - Pyspark
  - AWS RDS

## Results of Analyis
  - How many Vine reviews and non-Vine reviews were there?
   - ### Total Number of Reviews:
   - ![total number of reviews](https://github.com/stephenanayashilliard/Amazon_Vine_Analyis/blob/main/Resources/Total%20number%20of%20reviews.png)
   - ### Total Number of Vine Reviews:
   - ![total number of vine reviews](https://github.com/stephenanayashilliard/Amazon_Vine_Analyis/blob/main/Resources/total%20number%20of%20vine%20reviews.png)
   - ### Total Number of Non-Vine Reviews:
   - ![total number of non-vine reviews](https://github.com/stephenanayashilliard/Amazon_Vine_Analyis/blob/main/Resources/total%20number%20of%20reviews%2C%20non-vine.png)
  
  - How many Vine reviews were 5 stars?  How many non-Vine reviews were 5 stars?
  ### Total Vine Reviews with 5 Stars:
  ![5 star vine reviews](https://github.com/stephenanayashilliard/Amazon_Vine_Analyis/blob/main/Resources/5%20star%20vine%20reviews.png)
  ### Total Non-Vine Reviews with 5 Stars:
  ![5 star non-vine reviews](https://github.com/stephenanayashilliard/Amazon_Vine_Analyis/blob/main/Resources/5%20star%20non%20vine%20reviews.png)
  - What percentage of Vine reviews were 5 stars?  What percentage of non-Vine reviews were 5 stars?
  ### Percentage of 5 Star Vine Reviews:
  ![Vine %](https://github.com/stephenanayashilliard/Amazon_Vine_Analyis/blob/main/Resources/%25%20of%205%20Star%20vine%20reviews.png)
  ### Percentage of 5 Star Non-Vine Reviews:
  ![non-vine_%](https://github.com/stephenanayashilliard/Amazon_Vine_Analyis/blob/main/Resources/%25%20of%205%20star%20non-vine%20reviews.png)
## Summary
The summary states whether or not there is bias, and the results support this statement (2 pt)
An additional analysis is recommended to support the statement (2 pt)
    

