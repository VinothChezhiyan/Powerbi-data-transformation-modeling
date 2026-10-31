# Power BI – Data Transformation & Data Modeling

Two Power BI projects covering the full workflow: data transformation in Power Query, data modeling with relationships, DAX measures and interactive dashboards.

## Project 1: Sales Analysis (01_Sales_Analysis)
Data transformation and modeling on an orders dataset.

Power Query steps:
- Loaded List of Orders and Order Details tables
- Added a custom column: Profit Margin = Profit / Amount * 100
- Changed data types (Amount to Fixed Decimal, Date to Date type)
- Merged List of Orders with Order Details using Order ID
- Sorted Order Date in descending order
- Filtered State = Tamil Nadu
- Grouped by Category with Count, Sum and Average
- Added a Sales Target table by category

Data modeling:
- Created relationships between all tables using Order ID and Category

Files: Power_BI_File.pbix, Power_BI_Sales_Analysis.docx (step-by-step with screenshots)

## Project 2: Bike Station Analysis (02_Bike_Station_Analysis)
Analysis of 2,856 bike-sharing stations across 25 cities worldwide (2022–2025), covering station performance, utilization rates and cost efficiency.

- Cleaned and transformed the data in Power Query
- Built the data model and DAX measures
- Designed an interactive dashboard with KPI cards, bar, column, scatter and donut charts, and slicers

Files: BikeStation_Analysis.pbix, Bike_Station_Sharing_Data.docx (Power Query, data model, DAX and dashboard screenshots)

## Skills Demonstrated
Power Query (merge, filter, group by, custom columns, data types), data modeling and relationships, DAX measures, dashboard design, data visualization

## How to Open
Download the .pbix file and open it in Power BI Desktop (free).

Author: Vinoth C | linkedin.com/in/vinoth-data
