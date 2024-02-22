# Online-Sales-Analysis
An E-commerce Sales Company based in the United State seeks to create a sales dynamic dashboard with specific features to display year-to-date (YTD) sales information and generate insights for operational monitoring and strategic business decisions.

## Content
- [Introduction](#introduction)
- [Problem Statement](#problem_statement)
- [Project objectives](#project_objectives)
- [Data source](#data_source)
- [Data Visualization and Analytics](#data_visualization_and_analytics)
- [The key performance indicator for the different product categories](#the_key_performance_indicator_for_the_different_product_categories)
- [Sales Performance Segments by Region](#sales_performance_segments_by_region)
- [The best and worst-performing products](#The_best_and_worst_performing_products)
- [Sales Performance according to the type of shipment](#sales_performance_according_to_the_type_of_shipment)
- [Conclusion](#conclusion)
- [Recommendations](#Recommendations)

## Introduction
In the dynamic landscape of online commerce, businesses constantly seek innovative strategies to enhance their operational efficiency and customer service delivery.

A leading online business company in the United States has embarked on a project to create a dynamic dashboard. This dashboard is designed to present year-to-date (YTD) sales information, aiming to unlock valuable insights for improved business operations and customer service.

The initiative underscores the importance of data-driven decision-making in today’s competitive marketplace. By focusing on specific business questions related to key performance indicators, sales growth, regional sales performance, product performance, and shipping efficiency, the company is poised to make informed decisions that could significantly impact its growth and customer satisfaction levels.

## Problem Statement
The company would like to answer the following business questions in order to generate insights for operational improvement:

What are the year-to-date key performance indicators?
What is the year-on-year growth for each key performance indicator for the different product categories?
What are the sales performance segments by state and region?
What are the best and worst-performing products based on sales figures?
Which shipment type is generally performing better?

## Project objectives

Design and implement dynamic KPI dashboards that display crucial year-to-date sales metrics, including sales revenue, profit, quantity sold, and profit margin. These dashboards should provide real-time insights into business performance and facilitate quick decision-making.
Conduct a detailed analysis of the year-on-year sales growth for various product categories. This analysis should highlight areas of growth, and pinpoint categories requiring strategic intervention.
Utilize geographical data visualization tools to map year-to-date sales performance across different regions and states. This objective involves creating interactive maps and donut charts that offer a clear visual representation of sales distribution, aiding in the identification of high-performing and underperforming areas.
Analyze sales data to list the top 5 and bottom 5 products based on sales figures to provide actionable insights for inventory management and marketing strategies.
Break down sales performance by the type of shipping used, with the goal of determining the most effective shipping method. This analysis should consider customer satisfaction, cost-effectiveness, and delivery times.
Ensure that the dashboard and accompanying analyses empower stakeholders to make informed decisions. The insights provided should directly support strategic planning, operational improvements, and customer service enhancements.

## Data source
The dataset us_state_long_lat_codes.csv, obtained from “US State Boundaries — Opendatasoft”, contains geographical information for U.S. states. There are 52 entries.

The dataset 'ecommerce_data.csv', a dummy data for training purposes, contains 113,270 entries with 21 columns. Find data at Ecommerce Power BI Project — Google Drive

Import Datasets and Data Modeling
The two datasets were imported into Power BI, and a ‘Calendar table’ was created to enable time-series analysis.

The three tables were modelled by connecting the dimension tables to the fact table.

## Data Visualization and Analytics
The year-to-date key performance indicators

![image](https://github.com/Fkuukyee/E-commerce-Sales-Analysis/assets/147086232/5e767eef-d895-459d-a021-34c5de20afe1)

The KPI banner displaying the year-to-date and year-on-year growth in sales, profit, quantity sold, and profit margin is shown in Figure 1 above. These KPIs are crucial for businesses to monitor their performance over time. The percentage changes indicate the direction of the performance compared to a previous period.

YTD Sales stands for “Year-To-Date Sales,” which is the total sales revenue from the beginning of the current year to the present date. The value of $11.53 million shows a slight decrease of 0.83% year-on-year growth.
The year-to-date quantity of goods sold was 107,218 units, with a year-on-year growth of -7.29%.
The total profit earned for the current date shows $1.34 million, with a noticeable increase of 4.50% despite a slight decrease in sales of 0.83% and 7.29% in quantity of goods sold.
The profit margin achieved by the business stood at 11.58%, with a positive growth of 5.37%.

### The key performance indicator for the different product categories

![image](https://github.com/Fkuukyee/E-commerce-Sales-Analysis/assets/147086232/3c0f3e91-5a0b-465c-b382-a506800b8837)

Sales by product category are important for the company to assess the performance of the different product categories over time and adjust their strategies accordingly.

Office Supplies: The YTD sales for office supplies are $6.92 million, a decrease of 1.22% from the PYTD sales of $7.00 million.
Furniture: This category shows YTD sales of $2.52 million, which is a marginal increase of 0.73% from the PYTD sales of $2.50 million.
Technology: This category has year-to-date (YTD) sales of $2.10 million, which is slightly down from the prior year-to-date (PYTD) sales of $2.13 million, showing a decline of 1.37%.

### Sales Performance Segments by Region

![image](https://github.com/Fkuukyee/E-commerce-Sales-Analysis/assets/147086232/db9bfd3d-589f-472f-b1ae-879e67a6e7d9)  ![image](https://github.com/Fkuukyee/E-commerce-Sales-Analysis/assets/147086232/16d1dca1-21e5-4d99-998f-6fabe529fc23)

The chart visually represents the proportion of sales from each region, indicating that the West is currently the leading region in sales, followed by the East, Central, and South regions.
Sales by State (US Map): The map is interactive, and it allows users to filter the view by region and drill down to see state-level sales data.
These visualizations will help stakeholders quickly grasp the geographic distribution of sales and identify regions where the business is performing well or may need strategic focus.

### The best and worst-performing products

![image](https://github.com/Fkuukyee/E-commerce-Sales-Analysis/assets/147086232/86fe3e9f-d3a6-44b9-8d92-7ce563610089)

The staple envelope leads the sales, followed closely by staples, whereas Rediform S.O.S. is the least contributor to sales.

This information provides insight into inventory management and marketing priorities.

### Sales Performance according to the type of shipment

![image](https://github.com/Fkuukyee/E-commerce-Sales-Analysis/assets/147086232/39f57c27-e36f-4982-a95d-2825b6ec2840)

"Standard Class” shipping contributes the most to sales, accounting for over 60% of the total sales. “Second Class” follows with 19.22%, "First Class” with 15.10%, and finally, “Same Day” shipping has the smallest share with 5.17%.

### The Dynamic Dashboard

![image](https://github.com/Fkuukyee/E-commerce-Sales-Analysis/assets/147086232/d87edd0b-9328-4cd7-9cb2-506b4ebd4568)

This dashboard provides a comprehensive overview of sales performance across different categories and regions, along with insights into product performance and logistical preferences.

The slight decreases in sales and quantity sold indicate the need for strategic adjustments, while the positive profit margin shows effective pricing strategies.

The top and bottom products by sales give clear indicators of consumer preference and potential areas for inventory focus.

## Recommendations

- Analyze customer data to segment the market and tailor marketing strategies accordingly. Personalization can lead to improved customer engagement and higher sales by addressing specific needs and preferences.

- Utilize the insights on the best and worst-performing products to optimize inventory levels. Focus on stocking high-demand products while reducing or discontinuing underperforming ones.

- Evaluate the pricing strategies of different product categories, especially those showing a decline in sales. Competitive pricing, along with promotional offers, can attract more customers and boost sales volumes.

- Invest in targeted marketing campaigns for regions and states showing lower sales performance. Utilize data analytics to understand customer preferences in these areas and tailor marketing messages to address local demands.

- Considering the dominance of standard-class shipping, explore the feasibility of improving other shipment types to enhance customer satisfaction.

- Adopt a Data-Driven Culture: Regularly review dashboard insights and be agile in implementing changes based on data-driven evidence.

By adopting these recommendations, the company can address current challenges, capitalize on opportunities for growth, and sustain its competitive advantage in the online marketplace.

## Conclusion

The development of the online sales analysis dashboard represents a strategic endeavor by the online business company to leverage data for operational excellence and enhanced customer service.

Through detailed analysis and visualization of key performance indicators, product category performance, sales distribution by region and state, and shipping method efficiency, the dashboard provides a comprehensive overview of the company’s sales dynamics.

The insights gained from this dashboard are instrumental in identifying areas for improvement, strategic planning, and decision-making. Recommendations for addressing sales declines, capitalizing on regional strengths, and optimizing shipping methods offer a clear path forward. 

Ultimately, this project exemplifies the critical role of data analytics in modern business strategies, enabling the company to adapt to market trends, optimize operations, and achieve sustainable growth.








