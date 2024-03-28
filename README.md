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

## Question 1: Calculate Quantity of items, Sales value & Order quantity by each Subcategory in L12M

### _SQL Code_

![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/70b3eaab-b03c-4a38-8aa5-61041c9228c0)

### _Query result_


---
## Question 2: Calculate % YoY growth rate by SubCategory & release the top 3 categories with the highest growth rate. Can use metric: quantity_item. Round results to 2 decimal

### _SQL Code_

![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/8f13e0d4-92d2-4d76-b0ca-1a4bff609ad6)

### _Query result_



---
## Question 3: Ranking the Top 3 TeritoryID with the biggest Order quantity every year. If there's TerritoryID with the same quantity in a year, do not skip the rank number

### _SQL Code_

![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/d0aeaf2e-3f5d-441e-9dfc-48c6ca40bc5f)

### _Query result_



---
## Question 4: Calculate Total Discount Cost belongs to Seasonal Discount for each SubCategory

### _SQL Code_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/e00de6cf-9a0f-41d6-9941-c08ce0ceebcc)

### _Query result_


---
## Question 5:Retention rate of Customer in 2014 with status of Successfully Shipped (Cohort Analysis)

### _SQL Code_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/fbf7513e-362f-443c-a44b-cbcac5edf26b)


### _Query result_



---
## Question 6: Trend of Stock level & MoM diff % by all product in 2011. If %gr rate is null then 0. Round to 1 decimal

### _SQL Code_

![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/2a95993d-0d47-4af1-bda6-6777b7eac79d)

### _Query result_


---
## Question 7: Calculate MoM Ratio of Stock / Sales in 2011 by product name

### _SQL Code_

![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/61d44103-f224-4fb8-a296-f6f1fad68948)

### _Query result_


---
## Question 8: No of order and value at Pending status in 2014

### _SQL Code_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/b53d418e-5c23-470d-b800-901f19088477)

### _Query result_



