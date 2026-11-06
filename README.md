# Retail Sales Performance Analysis

## Project Overview
This project analyses retail sales performance using Microsoft Power BI. The main objective is to understand sales, profit, customer activity, product categories, and customer segments through an interactive dashboard.

## Tools & Technologies
- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)

## Dataset
The project uses the Sample Superstore dataset, which contains three tables:

- **Orders:** Sales transactions, customer details, product information, shipping details, and profit.
- **People:** Regional manager information.
- **Returns:** Information about returned orders.

## Project Workflow

### 1. Data Understanding and Cleaning
- Explored the Orders, People, and Returns tables.
- Promoted the first row as column headers.
- Checked and corrected column data types.
- Examined column quality and missing values.
- Checked duplicate records and identified expected duplicates.
- Validated sales, profit, discount, quantity, and date values.
- Verified that shipping dates were not earlier than order dates.

### 2. Data Modelling
- Created relationships between the three tables.
- Connected People and Orders using Region.
- Connected Returns and Orders using Order ID.
- Configured one-to-many relationships with single-direction filtering.
- Identified Orders as the main transaction (fact) table.

### 3. DAX Measures
Created the following measures:

- Total Sales
- Average Sales
- Total Profit
- Total Quantity
- Unique Orders
- Unique Customers
- Unique Return Orders
- Profit Percentage
- Average Order Value
- Return Rate

### 4. Dashboard Development

**KPI Cards**
- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Return Rate

**Visualisations**
- Sales Trend Over Time
- Sales by Category
- Sales by Segment
- Top 10 Products by Sales
- Profit by Category

**Interactive Slicers**
- Order Date
- Region
- Category
- Segment

## Skills Demonstrated
- Data cleaning and transformation using Power Query
- Data validation
- Data modelling and relationships
- Basic DAX calculations
- Data visualisation
- Interactive dashboard development

## Project Outcome
Developed an interactive retail sales dashboard to explore sales trends, profitability, product category performance, top-selling products, and customer segment contributions.

## Future Improvements
- Learn advanced DAX and time intelligence.
- Explore additional business performance metrics.
- Improve dashboard design and analytical depth.
- Develop additional Power BI projects using different datasets.
