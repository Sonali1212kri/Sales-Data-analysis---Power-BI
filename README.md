##  Sales-Data-analysis---Power-BI
This Power BI project — ElectroHub Sales Analysis — provides a comprehensive view of company sales performance through interactive dashboards. It enables data-driven decision-making by visualizing key performance indicators such as sales, profit, discount patterns, and product performance across different cities and time periods.

##  Project Objectives

# Top & Bottom 5 Analysis
   Identify the top 5 and bottom 5 products based on Sales, Profit, and Quantity Sold.
  Helps in understanding best-performing and underperforming products.
# Sales Trend Analysis
  Visualize Sales trends over time (daily, monthly, quarterly, annually).
  Detect seasonal trends and business growth patterns.
# Sales vs Profit Relationship
  Scatter plot to show correlation between Sales and Profit, helping to analyze profitability patterns.
# Comparative Analysis Between Two Time Periods
  Compare Sales, Profit, and Quantity Sold between any two date ranges selected via slicers.
# Discount Analysis
  Calculate and visualize Average Discount by Promotion Category (e.g., Flash Sale, Clearance Sale, Summer Sale, etc.).
# Order Summary
  Display total number of orders processed and their respective details.
# Detailed Table View
  Provide complete transactional-level data with filters for:
  Date
  Customer Name
  Product Name
  Promotion Category
  Includes key metrics like Net Sales, Profit, Discount, and Total Sales.
# Geographical Sales Visualization
Map visual showing Sales by City to identify regional performance trends.

## Dataset Structure

Fact Table: Contains transactional data including Sales, Profit, Quantity, Discount, etc.
Dimension Tables:
Dim Product
Dim Customer
Dim Promotion
Date Table

## Relationships: 
Established between fact and dimension tables using keys like ProductID, CustomerID, PromotionID, and Date.

## Key Visuals Used

Bar Chart: For Top/Bottom 5 product analysis.
Map Visual: To show Sales by City.
Scatter Plot: For Profit vs Net Sales correlation.
Line Chart: To show Sales trend by period.
Card Visuals: For total metrics like Sales, Profit, Orders, and Quantity.
Slicer: For date range and category-based filtering.
Table Visual: For detailed data view and filtering.

## Tools & Technologies

Power BI Desktop
Microsoft Excel / SQL Server (for data source)
DAX (Data Analysis Expressions) for calculated columns and measures.

## Key Insights

Apple iPhone 14 emerged as the top product by both sales and profit.
Tupperware Lunch Box showed lowest sales and profit performance.
Sales were highest during Flash Sales and Clearance Sales events.
Major sales hubs include Mumbai, Bangalore, Pune, and Delhi.
Profit strongly correlates with net sales, indicating efficient pricing and discount strategy.

## Learning Outcomes

  Data modeling and relationship creation in Power BI.
  DAX functions for dynamic KPIs and measures.
  Using slicers and filters for interactivity.
  Designing a clean, professional, and insightful dashboard.

## Dashboard Previews

  Top/Bottom 5 Sales Dashboard
  Overview Dashboard
  Data Filter Comparison Page 
  Detailed Order table 
Date Filter Comparison Page

Detailed Order Table
