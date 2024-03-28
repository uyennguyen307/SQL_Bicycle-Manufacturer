# I. Introduction
This project contains an eCommerce dataset that I will explore using SQL on Google BigQuery. The dataset is based on the Google Analytics public dataset and contains data from an eCommerce website.

# II. Requirements
Complete 08 query with expected output in Bigquery base on Google Analytics dataset to fulfill analysis requests.

# III. Dataset Access
The eCommerce dataset is stored in a public Google BigQuery dataset. To access the dataset, follow these steps:

Log in to your Google Cloud Platform account and create a new project.
Navigate to the BigQuery console and select your newly created project.
In the navigation panel, select "Add Data" and then "Search a project".
Enter the project ID "bigquery-public-data.google_analytics_sample.ga_sessions" and click "Enter".
Click on the "ga_sessions_" table to open it.

# IV. Explore Data
In this project, I will write 08 query in Bigquery base on Google Analytics dataset

https://console.cloud.google.com/bigquery?sq=86925067577:b7266a7f1e7c461a9c51373ea341c6f2

**Question 1: Calculate Quantity of items, Sales value & Order quantity by each Subcategory in L12M**

_**SQL Code**_

![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/ebeefb3c-b602-41af-b305-a5f2e2fd7e35)

_**Query result 1**_



---
**Question 2: Calculate % YoY growth rate by SubCategory & release the top 3 categories with the highest growth rate. Can use metric: quantity_item. Round results to 2 decimal**

_**SQL Code**_

![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/f7e977a9-82d6-48f7-afe3-79cf9f50c7ac)


_**Query result 2**_



---
**Question 3: Ranking the Top 3 TeritoryID with the biggest Order quantity every year. If there's TerritoryID with the same quantity in a year, do not skip the rank number**

_**SQL Code**_

![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/f35c7988-728e-44a6-ab54-63c8f8262e11)


_**Query result 3**_



---
**Question 4: Calculate Total Discount Cost belongs to Seasonal Discount for each SubCategory**

_**SQL Code**_



_**Query result 4**_




---
**Question 5:Retention rate of Customer in 2014 with status of Successfully Shipped (Cohort Analysis)**

_**SQL Code**_



_**Query result 5**_




---
**Question 6: Trend of Stock level & MoM diff % by all product in 2011. If %gr rate is null then 0. Round to 1 decimal**

_**SQL Code**_



_**Query result 6**_


---
**Question 7: Calculate MoM Ratio of Stock / Sales in 2011 by product name**

_**SQL Code**_



_**Query result 7**_




---
**Question 8: No of order and value at Pending status in 2014**

_**SQL Code**_


_**Query result 8**_



