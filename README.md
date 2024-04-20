# I. Introduction
This project contains an Adventure Wwork dataset that I will explore using SQL on Google BigQuery.

# II. Requirements
Complete 08 query with expected output in Bigquery based on the Adventure Wwork dataset to fulfill analysis requests.

# III. Dataset Access
The Adventure Wwork dataset is stored in a public Google BigQuery dataset. To access the dataset, follow these steps:

# IV. Explore Data
In this project, I will write 08 query in Bigquery base on the Adventure Wwork dataset

**Big Query Project Link:** https://console.cloud.google.com/bigquery?sq=86925067577:b7266a7f1e7c461a9c51373ea341c6f2

## Question 1: Calculate Quantity of items, Sales value & Order quantity by each Subcategory in L12M

### _SQL Code_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/70b3eaab-b03c-4a38-8aa5-61041c9228c0)

### _Query result_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/dfc1d020-6df4-4f80-90f3-5f233712be59)

---
## Question 2: Calculate % YoY growth rate by SubCategory & release the top 3 categories with the highest growth rate. Can use metric: quantity_item. Round results to 2 decimal

### _SQL Code_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/8f13e0d4-92d2-4d76-b0ca-1a4bff609ad6)

### _Query result_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/e68052a9-2bba-4eb7-93b5-3b1dc470ce4a)

---
## Question 3: Ranking the Top 3 TeritoryID with the biggest Order quantity every year. If there's TerritoryID with the same quantity in a year, do not skip the rank number

### _SQL Code_

![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/d0aeaf2e-3f5d-441e-9dfc-48c6ca40bc5f)

### _Query result_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/4e90f51a-0685-4b29-ab95-bc91af904d0c)

---
## Question 4: Calculate the Total Discount Cost belonging to Seasonal Discount for each SubCategory

### _SQL Code_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/e00de6cf-9a0f-41d6-9941-c08ce0ceebcc)

### _Query result_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/80d827d2-fd1e-4e51-a66e-423350a6474e)

---
## Question 5:Retention rate of Customers in 2014 with the status of Successfully Shipped (Cohort Analysis)

### _SQL Code_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/fbf7513e-362f-443c-a44b-cbcac5edf26b)

### _Query result_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/ee260056-4edf-4c54-a23b-2d0002fbbc49)

---
## Question 6: Trend of Stock level & MoM diff % by all product in 2011. If the  %growth rate is null then 0. Round to 1 decimal

### _SQL Code_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/2a95993d-0d47-4af1-bda6-6777b7eac79d)

### _Query result_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/6559fee6-44e2-45dd-be23-282d3d1a0a0f)

---
## Question 7: Calculate Month on Month Ratio of Stock / Sales in 2011 by product name

### _SQL Code_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/61d44103-f224-4fb8-a296-f6f1fad68948)

### _Query result_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/69d7114a-d2ca-4ae9-8a79-daf6390350db)

---
## Question 8: Number of orders and value at Pending status in 2014

### _SQL Code_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/b53d418e-5c23-470d-b800-901f19088477)

### _Query result_
![image](https://github.com/uyennguyen307/SQL_Bicycle-Manufacturer/assets/162019618/9b533ede-7b0c-4344-94fc-d5ac8d8bc79b)


