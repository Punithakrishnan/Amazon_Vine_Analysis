# Amazon_Vine_Analysis


## Overview 

---

This project included the analyzing Amazon reviews written by members of a paid Amazon Vine program or other reviewers to determine if there is any bias for favorable reiews by the reviewers in the Amazon Vine Program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

The goal of this project was to use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, PySpark was used to determine if there is any bias toward favorable reviews from Vine members in the dataset

--

Programming Tools:

Amazon AWS RDS Instance
pySpark
pgAdmin 4 (Prostgres SQL 14.2)
Google Colab Notebook
Git

## Results:

The ETL process of the Amazon Watches Reviews data (Amazon Watches Reviews) was performed in Google Colab Notebooks using pySpark. Figures 1 - 4 show the tables for customers, products, reviews, and vine reviews, respectively, after extracting and transforming data from the tsv file for Amazon "Watches" reviews. Figures 5 - 8 show the screenshots of SQL output after loading data into SQL tables in the Amazon AWS RDS instance. Figures 9 - 11 show dataframes for re-created vine table and it cleaning up stages. Figure 12 - 13 show final tables for Vine reviews and some statistics, respectively. Figure 14 - 15 show final tables for Non-Vine reviews and some statistics, respectively. Figure 16 and Figure 17 sho the review counts for Vine Reviews and Non-Vine reviews, respectively.

How many Vine reviews and non-Vine reviews were there?

There were 47 vine reviews and
There were 8362 non-Vine reviews
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There were 15 Vine reviews
There were 4332 non-Vine reviews
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

31.9% of Vine reviews were 5 stars
51.8% of non-Vine reviews were 5 stars
