#  🍕 Pizza Sales Analysis Dashboard (Power BI)

 # Project Overview

- This Power BI project analyzes the sales performance of a pizza company to identify best/worst-selling pizzas, sales trends, and customer ordering behavior.
  It provides insights into total revenue, order trends, popular pizza categories, and sales by size — helping management make better business decisions.

# Objectives

- To track and visualize key sales metrics such as revenue, total orders, and pizzas sold.
- To identify top-performing and underperforming pizza types.
- To analyze daily and monthly sales trends.
- To find which pizza size and category contribute most to revenue.
- To provide an interactive dashboard for exploring business performance.

# Dataset

-Source: Sample Pizza Sales dataset (Excel/CSV format)
- Time Period: January 2015 – December 2015

```
# Data Fields Include:
- pizza_id
- order_id
- pizza_name_id
- quantity
- order_date
- order_time
- unit_price
- total_price
- pizza_size
- pizza_category
- pizza_ingredients
- pizza_name
```

# Key Performance Indicators (KPIs)

# KPI	Description
- 💰 Total Revenue	₹817.86K
- 📦 Total Pizzas Sold	50K
- 🧾 Total Orders	21K
- 💵 Average Order Value (AOV)	₹38.31
- 🍕 Average Pizzas per Order	2.32


# Dashboard Insights

- Best / Worst Sellers
- Top Pizza by Revenue: The Thai Chicken Pizza
- Top Pizza by Quantity & Orders: The Classic Deluxe Pizza
- Lowest Seller: The Brie Carre Pizza

# Busiest Days & Times
- Peak Days: Friday & Saturday evenings
- Highest Monthly Orders: July and January

# Sales Performance

- Top Category: Classic Pizzas
- Top Size: Large Pizzas (45.89% of total sales)

# Visualizations Used

- KPI Cards
- Bar Charts (Top & Bottom 5 Pizzas)
- Line Chart (Monthly Order Trend)
- Column Chart (Daily Order Trend)
- Donut Charts (Sales by Category & Size)

# Tools & Technologies

- Power BI Desktop – for data visualization
- Excel – for data cleaning and preparation
- DAX – for calculated measures and KPIs
- Slicers
- navigators Buttons
- filiters

```
# Key DAX Measures
- Total Revenue = SUM(Pizza_Sales[Total Price])
- Total Orders = DISTINCTCOUNT(Pizza_Sales[Order ID])
- Avg Order Value = [Total Revenue] / [Total Orders]
- Total Pizzas Sold = SUM(Pizza_Sales[Quantity])
- Avg Pizzas per Order = [Total Pizzas Sold] / [Total Orders]
```

 # Dashboard Preview
 
- Overview Page
- Best/Worst Sellers Page

	
# How to Use

- Download the .pbix file from this repository.
- Open it in Power BI Desktop.
- Explore interactive visuals and filters.
- Use the date slicer or pizza category dropdown to analyze specific trends.

# Key Learnings

- Building multi-page Power BI dashboards
- Designing KPIs using DAX
- Performing data cleaning and transformation in Power Query
- Using visuals effectively for storytelling

🧑‍💻 Author

Dilip Kumar
💼 Aspiring Data Analyst
🔗 LinkedIn Profile[www.linkedin.com/in/redilip]
 | GitHub Projects[]
