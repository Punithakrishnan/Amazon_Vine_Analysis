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

<img width="530" alt="Screen Shot 2022-07-21 at 1 46 34 AM" src="https://user-images.githubusercontent.com/98849217/180138674-4a7b0cac-84c7-49ac-add4-a06a8462743e.png">

Figure 1. Screen shot showing customer table dataframe in pySpark (in Google Colab Notebook)


<img width="555" alt="Screen Shot 2022-07-21 at 1 48 20 AM" src="https://user-images.githubusercontent.com/98849217/180138882-cd771c03-e147-45e5-911a-e908df7513c4.png">

Figure 2. Screen shot showing products table dataframe in pySpark (in Google Colab Notebook)


<img width="746" alt="Screen Shot 2022-07-21 at 1 48 54 AM" src="https://user-images.githubusercontent.com/98849217/180138952-ee2fe71c-a441-48c8-8927-193b713482d3.png">

Figure 3. Screen shot showing reviews table dataframe in pySpark (in Google Colab Notebook)


<img width="810" alt="Screen Shot 2022-07-21 at 1 49 33 AM" src="https://user-images.githubusercontent.com/98849217/180139054-ae1573bb-0f7b-4dc2-9ccc-f7d502614ab7.png">

Figure 4. Screen shot showing vine table dataframe in pySpark (in Google Colab Notebook)


<img width="328" alt="Screen Shot 2022-07-21 at 1 53 20 AM" src="https://user-images.githubusercontent.com/98849217/180139536-eb6cab08-67b2-4b8d-b8b9-ac65789e5816.png">





<img width="710" alt="Screen Shot 2022-07-21 at 1 54 00 AM" src="https://user-images.githubusercontent.com/98849217/180139724-0af138dd-b564-42b4-a228-ece842ea349f.png">
