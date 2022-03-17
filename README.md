# Hive-Analytics-on-customer-demographics

**Buisness Problem**:

A company AdventureWorks wants to work on the database for its visiting customers and it is trying to analyse the year to date total revenue based on the database of retail sales data called adventure works. For this particular idea, company wants to use only customer, individual and credit card details. These datasets comprise of bulk and raw data that needs to be transformed and cleaned in order to bring out the data for analytics purpose and getting the insights out of it.

**Approach:**

Data is present in MySQL database.

Load the data from MySQL to HDFS using SQOOP.

Create and load data to HIVE table.

Read data from HIVE in Spark and perform data cleaning.

Load the data again to hive and perform analytics.


**HDFS EcoSystem**

Sqoop
Hive
SQL
PySpark


**Data Source Description**

Customer : This table contain all customer data related information.

![image](https://user-images.githubusercontent.com/100192514/158731332-4ff48f5c-7108-4358-a2db-c6cf3f42551b.png)


Individual: This table contain all Individual data information.

![image](https://user-images.githubusercontent.com/100192514/158732840-54a09ef7-230a-4c9e-8f0f-e4049a37f817.png)


Credit Card: This table contain all credit card data information.

![image](https://user-images.githubusercontent.com/100192514/158731403-652c39e6-0a6c-41ba-8b4f-0697a624a13e.png)


**ARCHITECTURE**

![image](https://user-images.githubusercontent.com/100192514/158731861-c527cfb1-3dd8-4856-9dc7-e24488604c1d.png)

