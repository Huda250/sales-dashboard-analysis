# sales-dashboard-analysis

##Project Overview

This project focuses on analyzing a sales dataset to extract key business insights and present them in a clear, interactive Excel dashboard. It includes product-level, city-level, and customer-level sales analysis, along with transaction and coupon behavior.


---

##Objective

Track overall sales performance

Identify top-performing products and customers

Analyze monthly sales and transaction trends

Understand coupon interaction behavior

Visualize insights in a user-friendly dashboard



---

##Dataset Description

The dataset includes:

Product name, quantity, average price

GST, delivery charges, discount

Transaction ID, customer ID

Date of transaction

Coupon status

City (location)



---

##Data Cleaning & Preparation

Removed duplicates and missing values

Standardized the Discount column and replaced "missing" values with 0 to allow numerical operations

Created a new column Grand Total using the formula:
(Quantity × Avg Price) - (Discount × Quantity × Avg Price) + (GST × Quantity × Avg Price) + Delivery Fee

Extracted month from the Date column for trend analysis



---

##Key Metrics (KPIs)

Sales Grand Total: $4,816,010.57

Total Transactions: 52,924

Average Transaction Value: $91.00

Coupon Usage Rate: 71.44%



---

##Visualizations

KPI Cards for sales total, transactions, average transaction, and coupon usage

Sales Trends by Month (line chart)

Transaction Volume per Month (bar chart)

Top 5 Best-Selling Products (horizontal bar chart)

Sales Distribution by City (pie chart)

Customer Interaction with Coupons (bar chart: clicked, used, not used)

Top 10 Customers by Revenue (table)



---

##Tools Used

Excel: Data cleaning, calculations, pivot tables, dashboard design

Pivot Tables: Used to group data by transaction, customer, product, and month



---

##Challenges & Limitations

Transaction Structure Complexity: Each transaction ID had multiple rows with separate GST, discount, and delivery charges, making transaction-level aggregation tricky.

Grand Total Calculation: Handled per row to reflect realistic item-level pricing and fees.

Coupon Behavior: Limited clarity on exact behavior mapping, so original categories were visualized directly.

Layout Constraint: Fitting all visualizations in a clean dashboard required prioritizing and organizing for clarity.



---

##Conclusion

This dashboard offers a comprehensive overview of sales activity, revealing top products, peak transaction periods, and customer engagement
