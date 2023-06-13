# Data Analyst Project : Business Decision Research

## Project Domain
The project domain is customer retention and sales analysis for DQLab Sport Center, a sports store that sells various sports-related items such as jackets, clothes, bags, and shoes.

## Business Understanding 
DQLab Sport Center has been operating since 2013 and has established a loyal customer base. However, they are facing a challenge of declining repeat purchases from their customers. To address this issue, they need to analyze the transactional data and identify the reasons for customer churn.

## Problem Statement
The problem faced by DQLab Sport Center is the decline in repeat purchases from customers, leading to customer churn. The store manager wants to understand the factors contributing to this churn and find potential strategies to improve customer retention.

## Goals
- Analyze the transactional data to identify patterns and trends related to customer churn.
- Determine the average transaction amount and frequency of purchases for both churned and retained customers.
- Identify the time duration between a customer's first and last transaction to determine churn.
- Identify potential factors that contribute to customer churn, such as long periods of inactivity or low average transaction amounts.
- Develop actionable insights and recommendations to improve customer retention and increase repeat purchases.

## Solution Statement
-  Identify potential factors contributing to customer churn. The analysis will focus on metrics such as average transaction amount, frequency of purchases, and time duration between transactions.
-  To predicting the churn, we will use Logistic Regression Model. Logistic Regression combines simplicity, interpretability, and predictive power, making it a reliable choice for churn analysis.

# Data Understanding

- No: Represents the row number or index of the data entry. It serves as a unique identifier for each record in the dataset.

- Row_Num: Represents the row number or index of the data entry.

- Customer_ID: This attribute represents the unique identifier for each customer. Each customer will have a distinct Customer_ID associated with them, allowing for tracking and analysis of individual customer behavior.

- Product: Indicates the type of product purchased in a particular transaction. It could include items like jackets, clothes, bags, shoes, or any other sports-related products offered by DQLab Sport Center.

- First_Transaction: This attribute represents the date or timestamp of the customer's first transaction with DQLab Sport Center. It helps to determine the customer's acquisition date and can be used to calculate metrics related to customer lifetime value.

- Last_Transaction: Represents the date or timestamp of the customer's most recent transaction with DQLab Sport Center. It indicates the latest interaction of the customer with the store, which is important for determining customer activity and identifying potential churn.

- Average_Transaction_Amount: Indicates the average amount spent by a customer in their transactions with DQLab Sport Center. It provides insights into customer spending patterns and can be used to segment customers based on their purchasing power.

- Count_Transaction: Represents the total number of transactions made by a customer during the available data period. It provides an understanding of the customer's purchase frequency and engagement with DQLab Sport Center.

