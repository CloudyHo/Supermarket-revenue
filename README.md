# Supermarket revenue
## 1. Project description
Revenue analysis over the years

## 2. Purpose and Outcome
Purpose: Analyze sales by region and identify the supermarket's best-selling products.
Outcome: A set of actionable insights that show which regions generate the most revenue and which specific products contribute the most to overall sales.

Link: Public dataset from Kaggle (Superstore Sales: https://www.kaggle.com/datasets/bhanupratapbiswas/superstore-sales/data)


## 3. Dataset
Row_ID: A unique identifier for each row in the dataset, used to differentiate records.
Order_ID: The order ID, a unique identifier for each order.
Order_Date: The order date, indicating the date the customer placed the order.
Ship_Date: The ship date, the date the order was shipped.
Ship_Mode: The shipping method, indicating how the order was shipped.
Customer_ID: The customer ID, a unique identifier for each customer.
Customer_Name: The name of the customer who placed the order.
Segment: The customer segment, indicating the classification of the customer.
Country: The country, indicating the country where the customer or the order is processed.
City: The city, where the customer resides or where the order is shipped to.
State: The state or province, indicating the geographical region at the state level where the customer lives.
Postal_Code: The postal code, a code used to determine the exact shipping location.
Region: The region, indicating the geographical region to which the customer belongs.
Product_ID: The product ID, a unique identifier for each product in the database.
Category: The product category, indicating the type of product.
Sub_Category: The product sub-category, a more specific classification within each category.
Product_Name: The product name, the detailed name of the product sold.
Sales: The sales amount, the revenue generated from the product in this order.

## 4. Result
### 4.1. Data cleaning
- After adding the file to colab, check how the data looks like.


- Change the format of the date columns and add month, year and delivery time columns.


### 4.2. Revenue Analysis

**4.2.1. Monthly sales revenue**

- Revenue comparison by month

1. Starting from August 2025, revenue is higher than in the first months of the year. Customers have a need to buy goods at the end of the year and that is also the peak season.

2. In 2016, revenue decreased significantly compared to the same period in 2015. By November, revenue began to increase again.

3. From 2017 onwards, the company has a fixed and loyal customer base. Therefore, revenue is also higher than in 2015.

**4.2.2. Compare sales and orders year by year**

- Total orders vs revenue analysis

1. In 2015, with about 2,000 orders, the revenue was nearly 500 thousand USD. But in 2016, more than 2,000 orders but the revenue was lower. Showing that the order value in 2016 was not as high as in 2015.

2. However, since 2017, the number of orders has increased, and the revenue has also increased significantly. From there, it can be seen that the order value also increases with each order.

**4.2.3. Average per order**


- Why is the order value getting lower every year?

1. In 2015, although the number of orders was low, the revenue was quite stable, the highest order value in 4 years.

2. In 2016, the number of orders increased, the revenue and value were lower than in 2015. This shows that customers spent less on each order.

3. In 2018, the number of orders and revenue were the highest, but the average order value was the lowest.

-> It may come from standard class customers, they dont spend much on each order or buy cheap products.

**4.2.4. Revenue during the week compared to the weekend**

Why is weekday sales higher than weekend sales?

1. Weekday sales are always much higher than weekend sales. It seems that consumer behavior mainly occurs on working days.

2. Our main customers are mainly from businesses and can also buy in large quantities.
