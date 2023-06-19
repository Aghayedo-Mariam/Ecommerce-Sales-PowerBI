# Ecommerce-Sales-PowerBI
# INTRODUCTION:
This Power BI project focuses on Ecommerce Sales Analysis, specifically in the Technology, Furniture, and Office Supplies categories.

## PROBLEM STATEMENT:
A US-based Ecommerce sales company has requested the creation of a sales dashboard with the following information and insights:

1. KPI Banner:
   - Display Year-to-date (YTD) Sales, YTD Profit, YTD Quantity Sold, and YTD Profit Margin.
   - Show Year-on-Year (YOY) Growth for each KPI.
   - Include a YTD Sparkline for each measure to visualize the monthly trend.

2. Sales by Customer Category:
   - Determine YTD Sales, Previous-year-to-date (PYTD) Sales, and YOY Sales Growth for different customer categories.
   - Add a trend icon for each category.

3. Sales Performance by State:
   - Analyze YTD Sales performance for each state.

4. Top and Bottom Products by Sales:
   - Identify the top 5 and bottom 5 products based on sales.

5. Regional Sales Analysis:
   - Determine YTD Sales by Region to identify the best and worst performing regions across the country.

6. Sales by Shipping Type:
   - Analyze YTD Sales by shipping type to determine the best shipping type percentage.
   
## THE STEPS USED IN ACHIEVING THIS PROJECT:

1. Importing Data: Importing the Ecommerce data table (21 columns, 113,270 rows) and the US-States-long and Lat-Codes table (4 columns, 52 rows).

2. Data Cleaning: Perform necessary data cleaning operations on the imported data.

3. Data Processing: Process the data for further analysis.

4. Data Modelling: Create entity relationships between the two tables, filter and replace customer state with names from the long-Lat data table, and establish relationships between the tables.

5. Creating Data Tables:
   - Utilize DAX expressions to create the Calendar table.
   - Add new columns for Year and Month extracted from the Calendar table.

## DATA VISUALIZATIONS:
The following visualization tools and techniques were used to present the analysis:

1. KPIs and DAX Workings:
   - I utilized KPI Cards, Area Charts, Matrix, Donut Charts, Maps, and Stacked Bar Charts.
   - I implemented calculations and DAX expressions for each KPI, including YTD Sales, PYTD Sales, YOY Sales, Sales Icons, Sales Icon Color, YTD Profit, PYTD Profit, YOY Profit, Profit Icons, Profit Color, YTD Quantity, YTD Concatenated Quantity, PYTD Quantity, YOY Quantity, Quantity Color, Quantity Icons, YTD Profit Margin, PYTD Profit Margin, YOY Profit Margin, Profit Margin Color, and Profit Margin Icons.

These steps and techniques were employed to achieve the desired KPIs and generate insightful visualizations.

