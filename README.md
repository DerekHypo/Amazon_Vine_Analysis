# Amazon_Vine_Analysis


## Overview of the analysis of the Vine program
Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

## Results
## Results

- How many Vine reviews and non-Vine reviews were there?

    There were a total of 65,581 vine reviews and 64,968 non-vine reviews.

![total_count](https://user-images.githubusercontent.com/67697826/212340999-54e1b95b-4461-469c-9946-83b1c07ad2f6.png)

![unpaid_count](https://user-images.githubusercontent.com/67697826/212341023-01299ff5-19cf-4fec-9f45-01a731d81bb1.png)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

    There were a total of 30,765 5-stars in the vine category to 30,543 5-stars in the non-vine category.
    
![five_star_count](https://user-images.githubusercontent.com/67697826/212343551-eebd41ca-4463-4085-83d3-da77906a08c3.png)


![five_star_unpaid](https://user-images.githubusercontent.com/67697826/212341728-5c7f9c96-2fd8-4ce9-9268-52b0f18029e7.png)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

    The percentages for 5 star Vine reviews is 36.22% of vine reviews to 47.01% of non-vine reviews
    
![paid_percentage](https://user-images.githubusercontent.com/67697826/212342986-0e5f3c56-5ab6-4cd6-83e8-91e36ed4302e.png)

![unpaid_percentage](https://user-images.githubusercontent.com/67697826/212343058-f8bc76b0-fb47-416c-b80a-85bacae90044.png)


## Summary

Further analysis would be need to review all 5-Star ratings for both Vine and Non-Vine members. Additionally, the use of other datasets could be used to verify or dispell the possibility of bias.
