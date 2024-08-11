****Amazon Sales Report Dashboard in Power BI****


This repository contains the dataset and instructions for creating a Power BI dashboard based on Amazon sales data. The dashboard provides insights into various aspects of sales performance, order fulfillment, and customer behavior.

Dataset Overview
The dataset, "Amazon Sale Report", includes detailed information about sales transactions on Amazon, including order details, product categories, shipping information, and transaction amounts.

File Details
Filename: Amazon Sale Report.csv


Columns: 24 columns (details below)


Rows: Each row represents an individual order.

***Column Descriptions***


**index**: Unique identifier for each record.


**Order ID**: Unique identifier for each order.


**Date**: Date of the order.


**Status**: Order status (e.g., Cancelled, Shipped, Delivered).


**Fulfilment**: Fulfillment method (e.g., Merchant, Amazon).


**Sales Channel**: Sales channel (e.g., Amazon.in).


**ship-service-level**: Level of shipping service (e.g., Standard, Expedited).



**SKU**: Stock Keeping Unit, a unique identifier for each product.


**Category**: Product category (e.g., Set, Kurta, Western Dress).


**Size**: Product size.


**ASIN**: Amazon Standard Identification Number.


**Courier Status**: Status of the courier.


**Qty**: Quantity of items in the order.


**currency**: Currency used for the transaction (e.g., INR).


**Amount**: Total amount of the order.


**ship-city**: City where the order was shipped.


**ship-state**: State where the order was shipped.


**ship-postal-code**: Postal code of the shipping address.


**ship-country**: Country where the order was shipped.


**promotion-ids**: Promotion IDs applied to the order.


**B2B**: Indicates whether the order is a Business-to-Business transaction.


**fulfilled-by**: Entity that fulfilled the order (e.g., Easy Ship).


****Power BI Dashboard Overview****
The Power BI dashboard built from this dataset will focus on the following key areas:

Sales Performance: Visualizing total sales, sales by category, and sales trends over time.


Order Fulfillment: Tracking fulfillment methods, courier statuses, and shipping service levels.


Geographical Insights: Analyzing sales distribution by city, state, and country.


Product Analysis: Understanding product performance through SKU, category, and style data


Customer Behavior: Examining customer preferences and order statuses.


***Usage Instructions***


**Importing the Dataset**:Load the CSV file into Power BI by selecting "Get Data" and choosing the CSV file option.

**Creating Visuals**:Use various Power BI visuals (e.g., bar charts, line charts, maps) to represent the data insights.

**Filtering and Slicing**:Apply filters based on date, status, category, and other relevant fields to drill down into specific data subsets.

**Refreshing Data**:If new data becomes available, refresh the dataset in Power BI to keep the dashboard up-to-date.
