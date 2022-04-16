# Amazon_Vine_Analysis

## Overview of the Analysis

### Purpose

Using PySpark to perform an ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.

### Background

Jennifer on the SellBy project gave us the task of analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

## Results

**These are the dataframes that we loaded onto pgAdmin.**

Review ID dataframe

![review_id](https://user-images.githubusercontent.com/95505596/163679126-ffe54b45-aabf-4c5a-ad96-b7e00394be4f.png)

Product ID dataframe

![product_id](https://user-images.githubusercontent.com/95505596/163679172-6976e162-8939-428d-8a57-3a0f841c1175.png)

Customer ID dataframe

![customer_id](https://user-images.githubusercontent.com/95505596/163679181-b1c80cad-ff4d-42f2-a03e-65ae3157eb81.png)

Vine ID dataframe

![vine_id](https://user-images.githubusercontent.com/95505596/163679190-d3183d6e-cd5c-4577-8eed-abc364b82b72.png)

------------------------------------------------------------

**Vine and non-Vine reviews**

- Vine Reviews

![vine_review](https://user-images.githubusercontent.com/95505596/163680356-86af853f-94c3-4d6a-9a8a-604492e54605.png)

- Non-Vine Reviews

![non_vine_review](https://user-images.githubusercontent.com/95505596/163680498-496854c5-7cc4-44c3-b648-b981f09906e3.png)

- 5-star Vine Reviews

![5_star_vine_review](https://user-images.githubusercontent.com/95505596/163680600-3802dd87-ec1e-4c83-b45b-b4728d901bc7.png)

- 5-star Non-Vine Reviews

![5_star_non_vine_review](https://user-images.githubusercontent.com/95505596/163680643-d0f837da-d448-43c2-9adb-0e17f5d146c3.png)

- 5-star Vine Review Percentage

![5_star_vine_review_percentage](https://user-images.githubusercontent.com/95505596/163680929-cfbace85-5bd9-4aae-8f7d-5954f39a8f83.png)

- 5-star Non-Vine Review Percentage

![5_star_non_vine_review_percentage](https://user-images.githubusercontent.com/95505596/163680960-7768a920-ca23-4c33-aadb-02c720369a12.png)

## Summary

According to our analysis we see that out of the 5-star reviews, 51% are vine reviews and 39% are non-vine reviews. This shows we have a positivity bias for reviews in the Vine program.

An additional analysis we can provide to support this statement would be to calculate the statistical distribution (mean, median, mode) of the star rating of Vine and non-Vine reviews.
