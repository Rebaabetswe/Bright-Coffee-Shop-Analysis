Bright Coffee shop analysis

Introduction

Bright Coffee Shop has appointed a new CEO. The CEO wants to grow the company's revenue and improve product performance. Using transactional data, this project highlights sales and product performance across three stores. It entails SQL-based data presentation, visualisation in Excel and a final presentation using Microsoft PowerPoint. The aim is to extract business insights to support data-driven decisions. Objectives include identifying which products generate the most revenue, determine the time of day when the store performs best, explore sales trends across different products and time intervals, and provide data-driven recommendations to improve overall sales performance.

Tools Used

•	Miro: Planning flow and project map

•	SQL (Snowflake): Aggregation, and transformations

•	Excel: Chart creation and dashboard data visualization

•	Microsoft PowerPoint: Final slide presentation design

Data Columns Provided

•	Transportation ID
•	Transaction date
•	-Transaction time
•	Transaction quantity
•	Store ID & Location
•	Product ID
•	Unit Price
•	Product type
•	-Product category
•	-Product details

Key Metrics Calculated

•	Total Revenue per store and product

•	Average Order Value (AOV)

•	Transaction volume by time and location

•	Weekly (Weekday vs Weekend) sales

•	Seasonal Sales

•	Hourly sales (Morning, Afternoon, Evening, Night)

•	Top 5 and Bottom 5 Selling Products

•	Product performance per store/location

•	-Month-to-Month growth

Visualisation and Chart types

•	Month-to-month growth - Line Chart

•	Top 5 and bottom 5 selling products - Pie Chart

•	Store level activity	Stacked - column chart

•	Hourly sales - Clustered bar chart

•	Seasonal sales - Clustered column chart

•	Average order value - Doughnut Chart

Key Business Insights

•	Autumn sales are highest across all stores, followed by Winter and Summer.
•	Morning hours generate the most revenue both weekdays and weekends, followed by afternoon. Weekends sales are the lowest.
•	Coffee and tea are the highest selling products across all stores.
•	Lower Manhattan contributes the highest total revenue, followed by Hell’s Kitchen.
•	All stores are contributing evenly towards the Average Order Value.
•	Total revenue grew steadily throughout the months and peaked in winter.
•	Store-level product preferences vary with Coffee and tea consistently contributing the highest to the total revenue.

SQL Summary (Snowflake)

•	SUM (), COUNT (), AVG () for key metrics

•	CASE statements for hourly, weekly, seasonal categories

•	TO_DATE () and TO_CHAR () for date formatting

•	GROUP BY used with store, product, category, date, etc.

Summary

The sales data reveals consistent performance across all stores. However, there are measures that can be put in place to better and optimise operations. Campaigns, loyalty points and promotions may assist with attracting more customers. By understanding time and location-based trends we can adjust the inventory to better suit our customers therefore increasing sales.
