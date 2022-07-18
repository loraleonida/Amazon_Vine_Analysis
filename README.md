# Amazon_Vine_Analysis

## Overview of the analysis: 
The purpose of this analysis was to perform the ETL process on a big data dataset from Amazon to analyze Amazon reviews written by the members of the paid Amazon Vine program to determine if there is any bias toward favorable reviews from Vine members. In this analysis, PySpark was used to perform the ETL process on the us_Books_v1_02 dataset to extract the dataset, transform the dataset, and finally connect to an AWS RDS instance and load the transformed data into pgAdmin. From there, Pandas was used for the analysis to determine any review bias by the Vine program members.

## Results: 

- How many Vine reviews and non-Vine reviews were there?
  - There were 0 Vine reviews and 403,807 non-Vine reviews.
  
  <img width="656" alt="Screen Shot 2022-07-17 at 4 59 26 PM" src="https://user-images.githubusercontent.com/101693004/179430146-190fa2d4-0848-485f-b27f-4c4be4848bc3.png">

<img width="651" alt="Screen Shot 2022-07-17 at 4 59 49 PM" src="https://user-images.githubusercontent.com/101693004/179430149-e3a82917-74b9-4e8c-b44c-8bb67c831e31.png">


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - There were 242,889 non-Vine 5 star reviews.
  - Because there were zero Vine reviews, there were zero Vine 5 star reviews.

<img width="523" alt="Screen Shot 2022-07-17 at 5 00 01 PM" src="https://user-images.githubusercontent.com/101693004/179430151-77d6a9c2-cbce-4deb-8057-8897682a6579.png">


- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - The percentage of 5 star non-Vine reviews was 60.15%
  - The percentage of 5 star Vine reviews was 0
  
  <img width="649" alt="Screen Shot 2022-07-17 at 5 00 10 PM" src="https://user-images.githubusercontent.com/101693004/179430156-be268335-e41a-42a8-9179-580d96ff12d0.png">



## Summary: 
Because this particular Books_v1_02 dataset did not have any Vine members, I was unable to determine if there was any positivity bias among the Vine member reviews. 
