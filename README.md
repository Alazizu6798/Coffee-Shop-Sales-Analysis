# Coffee Shop Sales Dashboard

# Project Objective
The primary aim was to empower the decision-makers of Coffee Shop with data-driven insights, fostering strategic growth and competitiveness in dynamic coffee shop industry.

## Dataset Used 
 - <a href="https://github.com/Alazizu6798/Coffee-Shop-Sales-Analysis/blob/main/Coffee%20Shop%20Sales.xlsx">Sales Data</a>
# Business Requirements

- Enhance understanding of sales dynamics and performance drivers.
- Identification of Geographical areas with high and low sales potential.
- Provide insights of product performance, aiding in inventory and marketing decisions.
- Inform pricing and margin strategies for improved profitability.
- Actionable recommendation for optimizing sales and profit across various dimensions.
# Question (KPIs)

1. Total Sales Analysis
-  Calculate the total sales for each respective month.
-  Determine the month-on-month increase or decrease in sales.
-  Calculate the difference in sales between the selected month and the previous month.
2. Total Orders Analysis:
-  Calculate the total number of orders for each respective month.
-  Determine the month-on-month increase or decrease in the number of orders.
-  Calculate the difference in the number of orders between the selected month and the previous month.
3. Total Quantity Sold Analysis:
-  Calculate the total quantity sold for each respective month.
-  Determine the month-on-month increase or decrease in the total quantity sold.
-  Calculate the difference in the total quantity sold between the selected month and the previous month.
4. Calendar Heat Map:
- Implement a calendar heat map that dynamically adjusts based on the selected month from a slicer.
- Each day on the calendar will be color-coded to represent sales volume, with darker shades indicating higher sales.
- Implement tooltips to display detailed metrics (Sales, Orders, Quantity) when hovering over a specific day.
5. Sales Analysis by Weekdays and Weekends:
- Segment sales data into weekdays and weekends to analyze performance variations.
- Provide insights into whether sales patterns differ significantly between weekdays and weekends.
6. Sales Analysis by Store Location:
- Visualize sales data by different store locations.
- Include month-over-month (MoM) difference metrics based on the selected month in the slicer.
- Highlight MoM sales increase or decrease for each store location to identify trends.
7. Daily Sales Analysis with Average Line:
- Display daily sales for the selected month with a line chart.
- Incorporate an average line on the chart to represent the average daily sales.
- Highlight bars exceeding or falling below the average sales to identify exceptional sales days.
8. Sales Analysis by Product Category:
- Analyze sales performance across different product categories.
- Provide insights into which product categories contribute the most to overall sales.
9. Top 10 Products by Sales:
- Identify and display the top 10 products based on sales volume.
- Allow users to quickly visualize the best-performing products in terms of sales.
10. Sales Analysis by Days and Hours:
- Utilize a heat map to visualize sales patterns by days and hours.
- Implement tooltips to display detailed metrics (Sales, Orders, Quantity) when hovering over a specific day-hour.
- Dashboard Interaction <a href="https://github.com/Alazizu6798/Coffee-Shop-Sales-Analysis/blob/main/Coffee%20shop%20sales%20Analysis.pbix">View Dashboard</a>
- SQL Process <a href="https://github.com/Alazizu6798/Coffee-Shop-Sales-Analysis/blob/main/MY%20SQL%20Queries.docx">Sql Queries<a/>

# Process
- Verified data for any  missing values and anomalies.
- Performed Data cleaning, changed some data types so that data is clean and consistent with respect to data type, data format and values using MySql.
- Used KPI card to display business requirements according to the questions asked.
- Used column chart to show Daily Sales Analysis with Average Line of total sales to identify exceptional sales days.
- Created Heat chart to display sales as per days specifically on particular hour.
- Created Calendar Heat Map in which each day will show sales volume.
- Used Donut chart to show sales by weekdays and weekends.
- Used Bar chart to analyze the sales distribution among various Stores and product category to visualize the contribution of Stores as per there location in total sales.
- Applied slicers to make it dynamic.

# Dashboard
![Screenshot(495)](https://github.com/Alazizu6798/Coffee-Shop-Sales-Analysis/blob/main/coffee%20shop%20dashboaard.png)

# Project Insights 
- Barista Espresso are more likely to be first priority of the customers.
- Highest Operating sales was done in month of June which was $166K..
 - Maximum number of Sales is done by Hell's Kitchen.
 - Profitable and large engagement time falls under first half of the day which is in between 7AM-11AM.
- There are large number of sales in weekdays as compared to weekends.
# Conclusion
The Coffee Shop Sales Dashboard successfully delivered actionable insights to support strategic decision-making. The analysis revealed that Barista Espresso is the top-performing product, while June marked the peak in sales at $166K. Hell's Kitchen emerged as the highest revenue-generating store, and customer engagement is strongest during weekday mornings (7 AM – 11 AM). Additionally, weekdays consistently outperform weekends in sales volume, indicating opportunities for targeted promotions during slower periods.
The use of dynamic visualizations, including calendar and hourly heatmaps, location-based comparisons, and performance KPIs, enabled a deeper understanding of sales patterns, customer behavior, and store performance. These insights can inform inventory planning, marketing strategies, and staffing decisions, ultimately driving growth and profitability.
