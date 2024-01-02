# E-commerce-Sales-Analysis
An E-commerce Sales Company based in the United State seeks to create a sales dynamic dashboard with specific features to display year-to-date (YTD) sales information and generate insights for operational monitoring and strategic business decisions.

## Content
- [Overview](#overview)
- [Requirements](#requirements)
- [Softwares used](#softwares_used)
- [Power BI Functionalities Used](#power_bi_functionalities_used)
- [Data source](#data_source)
- [Import Datasets and Data Modelling](#import_datasets_and_data_modelling)
- [Data Visualization and Dashboard](#data_visualization_and_dashboard)
- [Results and Findings](#results_and_findings)
- [Results and Findings](#results_and_findings)
- [KPI Banner](#kpi_banner)
- [Conclusion](#conclusion)
- [Recommendations](#Recommendations)

## Overview
The project focuses on creating a dynamic dashboard to display and analyze sales data. Key aspects include YTD sales, profit, quantity sold, and profit margin. The analysis utilizes Power BI, MS SQL Server, and data from Kaggle. Key findings indicate a slight decline in sales across customer segments in 2022 compared to 2021, with California leading in state-wise sales and the West region leading in regional sales. Standard Class shipping contributes most to sales.

## Requirements
- Create a KPI Banner showing YTD Sales, YTD Profit, YTD Quantity sold, YTD Profit Margin
- Find Year on Year growth for each KPI and show a YTD spark line for each measure in the KPI to understand the monthly trend for each fact
- Find YTD Sales, PYTD Sales, YoY Sales growth for different customer category. Add a trend icon for each category
- Find YTD Sales performance by each State: The dashboard should display sales performance broken down by state.
- Top 5 and Bottom 5 Products by Sales: Identifying the best and worst-performing products based on sales figures.
- YTD Sales by Region to know best and worst performing region all over country
- YTD Sales by Shipping Type to get the best shipping type percentage

## Softwares used 
- Power BI - Version: 2.116.966.0, 64-bit 
- MS SQL Server – 19.0.2
- Microsoft Excel-2021

## Power BI Functionalities Used
- How to connect Power BI to MS SQL server and Flat Files
- Data Modeling with three tables
- Data cleaning in Power Query
- How to create a Date Table in Power BI
- Time Intelligence function (TOTALYTD, SAMEPERIODLASTYEAR)
- Creating Dynamic and Complex KPI’s
- Basic to Advanced Dax Queries
-	Conditional Formatting's, Adding dynamic icons in Power BI
-	Different DAX functions like Calculate, Sum, Sumx, Filter, values, selectedvalue, return, concatenate, divide, var, etc.
-	Creating different charts, maps and formatting them

## Data source
The primary data sets were obtained from Kaggle (https://www.kaggle.com/datasets/iabdulw/ecommerce-customer-data) 
The dataset ‘ecommerce_data.csv’ cover various aspects of ecommerce sales and financial metrics like sales and profit. It contains 113,270 entries with 21 columns.The dataset 'us_state_long_lat_codes.csv' contains geographical information for U.S. states. There are 52 entrie.

## Import Datasets and Data Modelling
The two datasets were imported into the Microsoft SQL server to. Power BI was then connected to MS SQL Database. A ‘Calendar table’ was created, and the three tables were modelled by connecting the dimension tables ‘Calendar table’ and ‘us_state_long_lat_codes” table to the fact table Ecommerce.

## Data Visualization and Dashboard
![image](https://github.com/Fkuukyee/E-commerce-Sales-Analysis/assets/147086232/cafcfd47-482e-4f93-b56a-2703b3f2767d)

Refer to Ecommerce dashboard.pbix for the interactive dashboard.

## Results and Findings

## KPI Banner 
### YTD Sales, Profit, Quantity Sold, Profit Margin
- YTD Sales: $11,533,640.96
-	YTD Profit: $1,335,266.99
-	YTD Quantity Sold: 107,218 units
-	YTD Profit Margin: 11.58%

### Year on Year Growth 
-	YoY Sales Growth: -0.83%
- YoY Profit Growth: 4.50%
- YoY Quantity Sold Growth: -7.29%

### Sales by Customer Category 
#### Consumer Segment:
- YTD Sales 2022: $5,978,216
- YTD Sales 2021: $6,010,983
- YoY Sales Growth: -0.55%

#### Corporate Segment:
- YTD Sales 2022: $3,496,845
- YTD Sales 2021: $3,519,911
YoY Sales Growth: -0.66%

### Home Office Segment:
- YTD Sales 2022: $2,058,580
- YTD Sales 2021: $2,099,128
- YoY Sales Growth: -1.93%

### YTD Sales Performance by State
California leads in sales with $2,335,532 followed by New York and Texas . Refer to report for details.

### Top and Bottom  5 Products by Sales
Staple envelope is the hightest performing product with $57,090.84 in sales whiles Eldon Jumbo ProFile Portable File Boxes Graphite/Black is the worst with $379.89 in sales.
Refer to dashboard for more.

### YTD Sales by Region
The West region leads in sales, followed by the East, Central, and South regions.

### YTD Sales by Shipping Type
"Standard Class" shipping contributes the most to sales, accounting for over 60% of the total sales. "Second Class" follows, then "First Class," and finally, "Same Day" shipping has the smallest share.

### Conclusion 
Key findings indicate a slight decline in sales across customer segments in 2022 compared to 2021, with California leading in state-wise sales and the West region leading in regional sales. Standard Class shipping contributes most to sales.

### Recommendations
-	Investigate the causes of sales decline across customer segments and states, focusing on market trends or customer preferences changes.
-	Analyze the high performance of the West region and California to replicate successful strategies in other regions and states.
-	Explore the potential to enhance sales through different shipping types, given the dominance of Standard Class shipping.


