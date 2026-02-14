UrbanKartAnalytitcs-PowerBi-Dashboard

This project Transforms the raw data into actionable insights using SQL and Power BI.

The dashboard is designed to help decision-makers quickly understand performance, identify inefficiencies, and evaluate growth opportunities across sales, products, customers, and marketing campaigns.

The dashboard answers the following critical business questions:
 Sales & Profitability
- How is revenue, profit, and order volume trending over time?
- Which product categories and brands contribute the most to revenue and profit?
- Are profits growing at the same pace as revenue?

Product Performance
- Which subcategories are the most profitable and which underperform?
- Are there products generating high revenue but low profit margins?
- Which products have the highest return rates?

Customer Analytics
- How is the customer base growing over time?
- Which age groups and categories drive the most customer engagement?
- What is the average customer lifetime value?

Marketing Campaign Effectiveness
- Which marketing channels generate the most conversions?
- How efficient is marketing spend across channels?
- Are higher spends translating into higher conversions?

Project Workflow

1. Raw Data Analysis 
   Initial exploration of sales, customer, product, and marketing campaign data to identify quality issues and inconsistencies.

2. Data Cleaning & Transformation (PostGreSQL) 
   SQL was used to clean, standardize, and prepare the data, including handling missing values, removing duplicates, and creating derived fields.

3. Table Creation & Schema Design
   Cleaned data was structured into fact and dimension tables using a star schema approach to support scalable analytics.

4. Data Modeling in Power BI  
   Tables were connected using optimized relationships and a dedicated Calendar table to enable accurate time intelligence.

5. Dashboard Development 
   Interactive dashboards were built to provide clear, business-focused insights with consistent design and navigation.

Dashboard Pages

 Executive Summary_dashboard
High-level KPIs and overall business performance trends.


 Sales_dashboard
Revenue, profit, and order trends across time, categories, and brands.

 products_dashboard
Profitability analysis, top and bottom subcategories, and return insights.

 Customers_dashboard
Customer growth trends, segmentation, and lifetime value metrics.

 Marketing Campaigns_Dashboard
Campaign spend, conversions, and channel efficiency analysis.


Tools Used
- SQL (For Data cleaning, transformation, schema design)
- Power BI Desktop(For Data Modeling,Creating DAX Measures to show insights and deeper analysis, Visualize Data)
