# Coffee_Shop_Sales_DataAnalysis


## Overview

The **Coffee Sales Data Analysis** provides a detailed overview of coffee sales performance, trends, and insights. Built entirely using **Power BI**, this dashboard helps visualize key sales metrics such as revenue, sales volume, product performance, and regional breakdowns. It is designed to assist sales managers and business owners in making data-driven decisions to improve sales strategy and optimize inventory.

## Features

- **Revenue Overview**: A snapshot of total sales revenue over a given period.
- **Sales by Product**: Breakdown of sales performance by different coffee products.
- **Region-wise Sales**: Analyze sales across various regions and identify top-performing areas.
- **Monthly and Yearly Trends**: Visualize sales trends over time, including seasonality and growth patterns.
- **Top-selling Products**: Identify the best-performing coffee products based on sales volume and revenue.
- **Interactive Filters**: Dynamic filtering options to view sales data by region, product type, and time period.

## Technologies Used

- **MS EXCEL**: Utilized for data cleaning, analysis, and creating the dashboard using charts, pivot tables, and slicers.

## Objective of this Analysis

The main objective of this project is to analyze retail sales data to gain the actionable insights that will enhance the performance of the coffee shop.

## Scope

- **Data Collection**: Gather and verify sales data, including transactions, product details, and dates.
- **Data Cleaning**: Import data into Power Query, clean up errors, and organize it into structured tables.
- **Data Analysis**: Calculate key metrics like total sales and average transaction value. Identify sales trends and customer preferences.
- **Visualization**: Create charts and graphs (line, bar, pie) to represent data trends and comparisons.
- **Reporting**: Develop a dashboard summarizing key metrics and visualizations. Write a report with insights and recommendations for improving sales strategies.
- **Presentation**: Prepare a presentation with clear slides to share findings and recommendations with stakeholders.


## Recommended Analysis and its Results

- **How do sales vary by day of the week and hour of the day?**: Results are showed in the Report Chart.
- **Are there any peak times for sales activity?**: As per the Report chart, it has shown that, the peak times are between 8-10.
- **What is the total sales revenue for each month?**: Results are showed in the Report Chart.
- **How do sales vary across different store locations?**: Results are showed in the Report Chart.
- **What is the average price/order per person?**: Results are showed in the Report Chart. It is Average Price per person is 4.69 and Average Order per person is 1.44.
- **Which products are the best-selling in terms of quantity and revenue?**: **Coffee and Tea** products are the best-selling products in terms of Quantity and Revenue.
- **How do sales vary by product category and type?**: Results are showed in the Report Chart.

### Mock-up Dashboard
![mock up dashboard_Coffee_shop_sales](https://github.com/Yashwanth-GS/Coffee_Shop_Sales_DataAnalysis/blob/911f5553c20680994a511c7bbe3f40c9705757dd/Screenshots/Screenshot%202025-02-17%20204829.png)

![mock up dashboard_Coffee_shop_sales](https://github.com/Yashwanth-GS/Coffee_Shop_Sales_DataAnalysis/blob/b5ce9f9512b3d7fc1008bfac67026033cd151f54/Screenshots/Screenshot%202025-02-17%20204909.png)

## **DAX Measures used in the Analysis**
- **Average_Bill**: = SUM(Transactions[Total_bill])/COUNT(Transactions[transaction_id])
- **Average_Order**: = SUM(Transactions[transaction_qty])/DISTINCTCOUNT(Transactions[transaction_id])
- **Foodfall**: = DISTINCTCOUNT(Transactions[transaction_id])
- **Sales**: = SUM(Transactions[Total_bill]) 

## 💬 Feedback and Questions

If you have any feedback or questions about the project, please feel free to ask. We appreciate your input and are here to help. You can reach out by opening an issue on GitHub or by emailing me at [yashgs97312@gmail.com].

Thank you for exploring the **Coffee Shop Sales Data Analysis** Project! We hope you find it useful and informative.

Happy Analyzing!
