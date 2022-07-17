# Amazon_Vine_Analysis

## Overview of the analysis: 
The purpose of this analysis was to perform the ETL process on a big data dataset from Amazon to analyze Amazon reviews written by the members of the paid Amazon Vine program to determine if there is any bias toward favorable reviews from Vine members. In this analysis, PySpark was used to perform the ETL process on the us_Books_v1_02 dataset to extract the dataset, transform the dataset, and finally connect to an AWS RDS instance and load the transformed data into pgAdmin. From there, Pandas was used for the analysis to determine any review bias by the Vine program members.

## Results: 
Using bulleted lists and images of DataFrames as support, address the following questions:

- How many Vine reviews and non-Vine reviews were there?
  - There were 0 Vine reviews and 403,807 non-Vine reviews.

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - There were 242,889 non-Vine 5 star reviews.
  - Because there were zero Vine reviews, there were zero Vine 5 star reviews.

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - The percentage of 5 star non-Vine reviews was 60.15%
  - The percentage of 5 star Vine reviews was 0


## Summary: 
Because this particular Books_v1_02 dataset did not have any Vine members, I was unable to determine if there was any positivity bias among the Vine member reviews. 
