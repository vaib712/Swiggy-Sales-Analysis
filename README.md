# Swiggy Sales Analysis Dashboard
An end-to-end sales analytics project built in Microsoft Excel, analyzing ~197K+ food delivery order records from Swiggy to uncover revenue trends, customer rating patterns, and regional performance across India. The project transforms raw transactional data into an interactive, decision-ready dashboard using PivotTables, PivotCharts, and dynamic slicers.

![Dashboard](<Swiggy Sales Analysis Dashboard.png>)

### Project Overview

Swiggy, one of India's leading food delivery platforms, generates massive volumes of order-level data every day. This project simulates a real-world business analytics scenario: taking a raw, unaggregated dataset and converting it into actionable insights that a business or operations team could use to track performance, identify top-performing regions, and understand customer behavior.

The workbook is structured across three sheets, mirroring a standard analyst workflow:

Sheets/ Purpose
1. Source Data - Raw, order-level dataset (~197,430 rows × 14 columns)
2. Analysis - 	PivotTables powering every KPI, trend, and breakdown on the dashboard
3. Dashboard - 	Consolidated, interactive visual report

### Objective

To design a dynamic Excel dashboard that answers key business questions:

1. What is the overall sales performance, and how is it trending month-over-month, week-over-week, and day-over-day?
2. Which states and cities are driving the most revenue?
3. How do customer ratings and order volumes vary by quarter?
4. What is the split between Veg and Non-Veg orders?
5. Which days of the week see peak ordering activity?

### Dataset

The source data contains granular, order-level records with the following fields:

State, City, Day, Order Date, Week, Quarter, Restaurant Name, Location, Category, Dish Name, Food Type (Veg/Non-Veg), Price (INR), Rating, Rating Count

Scale: ~197,000+ individual order records spanning 8 months (Jan–Aug), across multiple Indian states and cities.

### Tools & Techniques Used
1. Microsoft Excel — PivotTables & PivotCharts for aggregation and trend analysis
2. Slicers & Timelines — for interactive, user-driven filtering by month
3. Doughnut, Line, Bar, and Column Charts — for multi-dimensional visual storytelling
4. Filled Map Chart — for geographic (state-wise) sales visualization
5. KPI Cards — built using linked cells to summarize headline metrics at a glance
6. Data Aggregation Functions — SUM, AVERAGE, COUNT, and PivotTable summarization (Sum of Price, Average of Rating, Sum of Rating Count, Count of Dish Name)
7. Dashboard Design Principles — consistent color theming, card-based KPI layout, and single-page executive summary format

### Dashboard Features
1. Key Performance Indicators (KPIs)
2. Total Sales: ₹53.01M
3. Average Rating: 4.34 / 5
4. Average Order Value (AOV): ₹268.51
5. Total Rating Count: 5.59M
6. Total Orders: 197.43K

### Visual Breakdowns
1. Monthly Sales Trend — line chart tracking revenue across Jan–Aug
2. Daily Sales Trend — bar chart comparing sales by day of the week (Sun–Sat)
3. Weekly Sales Trend — 36-week rolling column chart for granular trend detection
4. Total Sales by Food Type — doughnut chart showing a 63% Veg / 37% Non-Veg order split
5. Quarterly Performance Table — Sales, Average Rating, and Order volume broken down by Q1–Q3
6. Top 5 Cities by Sales — Bengaluru, Lucknow, Hyderabad, Mumbai, and New Delhi ranked by revenue
7. State-Wise Sales Map — filled geographic map visualizing revenue distribution across Indian states
8. Interactive Month Slicer — enables users to filter the entire dashboard by any combination of months

### Key Insights
1. Bengaluru dominates regional sales, generating nearly 2× the revenue of the next closest city (Lucknow, Hyderabad, and Mumbai are closely clustered).
2. Vegetarian orders account for 63% of total sales volume, indicating a strong customer preference that could inform restaurant partnerships and inventory strategy.
3. Customer satisfaction remains consistently high and stable, with average ratings holding steady at 4.3 across all three quarters — suggesting reliable service quality even as order volume scales.
4. Q3 shows a dip in total sales and order volume relative to Q1 and Q2, a signal worth investigating for seasonality or operational factors.
5. Saturday is the peak ordering day, with daily sales trending upward through the week — useful for staffing and demand-planning decisions.

### Skills Demonstrated
1. Large-scale data handling and cleaning (~200K rows) in Excel
2. PivotTable-driven aggregation and multi-dimensional analysis
3. Dashboard design and data storytelling for non-technical stakeholders
4. KPI definition and business metric calculation (AOV, rating trends, sales trends)
5. Geographic and time-series data visualization
6. Building interactive, filter-driven reporting tools

### Repository Contents

Swiggy_Analysis_Project.xlsx
Swiggy_Sales_Analysis_Dashboard.png
README.md

#### How to Use
1. Download Swiggy_Analysis_Project.xlsx
2. Open in Microsoft Excel (2016 or later recommended for full PivotChart/slicer support)
3. Navigate to the DASHBOARD sheet
4. Use the Months slicer on the left panel to filter insights by any combination of months
5. Explore the Analysis sheet to see the underlying PivotTables driving each visual.

### About This Project

This project was built as part of my data analyst portfolio to demonstrate practical skills in data cleaning, aggregation, visualization, and dashboard design using Excel — mirroring the kind of ad hoc business reporting analysts are frequently asked to deliver in real roles.

Connect with me: [Vaibhavr712@gmail.com]