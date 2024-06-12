# Sales-Data-Exploration.

## Project Overview
This project demonstrates a series of SQL queries used to analyze and extract meaningful insights from a sales database. The database consists of multiple tables, including regions, sales representatives, accounts, orders, and web events. Each query is designed to perform specific data retrieval and aggregation tasks to support business analysis.

## Queries Included
### Regional Sales Representative Accounts

Retrieve the names of accounts managed by sales representatives in the Midwest region.
Filter representatives with names starting with 'S' or containing ' K'.

### Order Analysis

Calculate the unit price of orders where standard quantity exceeds 100.
Further filter orders where poster quantity exceeds 50 and sort by unit price in ascending and descending order.
Analyze orders with lower thresholds for standard and poster quantities.

### Average Order Amounts

Compute average amounts for standard, gloss, and poster orders grouped by account.
Calculate total average order amounts and sort accounts by total amount in descending order.

### Web Events Analysis

Count the occurrences of web event channels grouped by sales representatives and sort by frequency.

### Yearly and Monthly Sales Summary

Summarize total sales amounts by year and sort in ascending order.
Focus on specific years (2013 and 2017) and group by year and month.
Analyze daily sales totals for the year 2017 and specific dates.

### Account-Specific Analysis

Provide detailed monthly gloss total sales for a specific account (e.g., Walmart) and identify the peak sales month.

## Usage
Each SQL query in this project is designed to address different analytical needs and can be executed in a SQL environment that supports standard SQL syntax. To use these queries:

Ensure your SQL database is properly set up with the required tables and data.
Copy and paste the desired query into your SQL editor or command-line interface.
Execute the query to retrieve results.

## Conclusion
This project showcases the versatility of SQL in performing complex data analysis tasks. By utilizing joins, aggregations, and filters, these queries provide valuable insights into sales performance, regional activities, and customer behaviors. The approach can be adapted and extended to meet additional analytical requirements.
