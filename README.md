# Bright-Motors-CAR-ANALYSIS
Analysis of Bright Motors car sales data using Databricks and SQL to uncover revenue drivers, regional performance, and customer trends, with actionable insights to improve profitability and inventory efficiency.

Bright Motors Car Sales Analysis.
----------------------------------------------------------------------
Project Overview
------------------
This project analyzes the Bright Car Sales dataset to generate actionable insights that support strategic decision-making at Bright Motors. The analysis focuses on improving sales performance, optimizing inventory, and identifying growth opportunities across regions and vehicle segments.

Objectives
----------
The key objectives of this analysis are to:
------------------------------------------
Identify car makes and models that generate the highest revenue
Examine the relationship between selling price, mileage, and year of manufacture
Evaluate regional sales performance
Identify trends in customer purchasing behavior
Provide recommendations to improve profitability and operational efficiency
Tools and Technologies
Data Processing and SQL: Databricks (Spark SQL)
Data Visualization: Microsoft Excel / Power BI
Presentation: Microsoft PowerPoint / Canva
Planning and Architecture: Miro
Data Architecture

The project follows a structured data pipeline:
----------------------------------------------
Source Layer
Raw dataset in Excel/CSV format
ETL Layer
Data cleaning and transformation:
Removal of duplicates
Handling missing values
Conversion of price fields from text to numeric format
Storage Layer
Processed data stored in Databricks tables
Analysis Layer
Data transformation and aggregation using Spark SQL
Visualization Layer
Dashboard creation in Excel or Power BI
Presentation Layer
Insights presented using PowerPoint or Canva

Key Calculations
----------------
Total Revenue
total_revenue = selling_price * units_sold

Profit Margin
profit_margin = (selling_price - cost_price) / selling_price * 100

Performance Tiers
------------------
High Margin
Medium Margin
Low Margin

Grouping Dimensions
--------------------------
Make
Model
Year
Region
Fuel Type
Time (Month, Quarter, Year)
Data Processing Steps
Converted the dataset from Excel to CSV format
Loaded the dataset into Databricks
Cleaned and standardized the data
Converted price columns to numeric format
Created calculated columns:
total_revenue
profit_margin
Categorized vehicles into margin performance tiers
Aggregated data across time periods and regions
Key Insights Delivered
Revenue contribution by car make and model
Sales distribution by year and fuel type
Regional performance across cities or provinces
Trends in average selling price over time
Identification of high-performing vehicle segments
Dashboard Features
Interactive filters for:
Region
Fuel Type
Year

Key performance indicators:
-----------------------------

Total Revenue
Units Sold
Average Selling Price
Profit Margin

Recommendations
---------------------------------
Prioritize high-revenue and high-margin vehicle models
Expand operations in top-performing regions
Adjust pricing strategies based on observed trends
Align inventory with customer demand patterns
Reduce excess inventory to minimize holding costs

Project Deliverables
---------------------
Architecture Diagram (Miro)

Processed Dataset: 
----------------
car_sales_processed.xlsx

Presentation:
----------------
BrightMotors_Presentation.pdf
SQL Script:
-------------
car_sales_queries.sql

How to Use
--------------
Clone the repository
Upload the dataset to Databricks
Execute the SQL scripts provided
Connect Power BI or Excel to the processed dataset
Review the presentation for insights and recommendations.
For questions or collaboration, please reach out via GitHub or LinkedIn.
