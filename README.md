# Sales Performance Analysis Dashboard

## Project Overview
This project features an interactive Tableau dashboard designed to analyze sales performance using the "Sample - Superstore" dataset. It provides insights into sales trends, subcategory performance, geographic sales distribution, and customer behavior. The dashboard helps users identify key areas of growth, profitability, and operational improvements.

---

## Dataset Description

### Data Source
- **Dataset Name:** Sample - Superstore
- **Type:** Microsoft Excel Workbook
- **Sheets Used:**
  - **Orders:** Contains primary transactional data (e.g., sales, profit, shipping, and customer information).
  - **People:** Provides details about regional sales representatives.
  - **Returns:** Tracks order returns by Order ID.

### Key Fields in Orders Sheet
- **Order ID:** Unique identifier for each order.
- **Order Date & Ship Date:** Dates for order placement and shipment.
- **Ship Mode:** Delivery method (e.g., Standard Class, First Class).
- **Customer Info:** Name, Segment (Consumer, Corporate, Home Office).
- **Region & Geography:** City, State, Region, Postal Code.
- **Product Info:** Category, Sub-Category.
- **Sales, Quantity, Discount, Profit:** Financial and operational metrics.

### Relationships
- **Orders.Order ID ↔ Returns.Order ID**
- **Orders.Region ↔ People.Region**

---

## Dashboard Features

### 1. **Yearly Sales Performance**
   - **Interactive Timeline (2021-2024):** Filter sales data by year.
   - **Visualizations:** 
     - Weekly and monthly sales trends.
     - Year-over-year performance comparison.

### 2. **Subcategory Sales Analysis**
   - **Visualizations:**
     - Bar chart and marginal histogram showcasing total sales by subcategories.
     - Identifies top-performing and underperforming product subcategories.

### 3. **Geographic Sales Insights**
   - **Map Visualization:**
     - State-wise sales data with a gradient color scale for sales volume.
     - Hover tooltips for detailed state-level metrics.

### 4. **Returns Analysis**
   - Tracks products and regions with high return rates.
   - Helps assess customer satisfaction and operational issues.

---

## How to Use the Dashboard

1. **Open the Tableau File:**
   - Load the "Sample - Superstore" Excel file in Tableau.
   - Navigate to the “Sales Performance” dashboard.

2. **Interact with Filters:**
   - **Years:** Use the timeline to filter data for specific years.
   - **Regions/States:** Click on the map or filter regions to analyze sales geographically.
   - **Subcategories:** Drill down into product performance using bar charts and histograms.

3. **Explore Data Relationships:**
   - Analyze trends in sales, profit, and returns over time and across different dimensions (e.g., subcategories, regions).

4. **Actionable Insights:**
   - Compare sales trends by year to identify growth patterns.
   - Focus on underperforming subcategories or regions for improvement.
   - Use returns data to optimize product quality and delivery processes.

---

## Insights and Takeaways

1. **Top Performers:**
   - Subcategories like Phones and Chairs lead in sales.
   - California and Texas exhibit the highest state-level sales.

2. **Profitability Trends:**
   - Certain subcategories with high sales, like Technology, show low profit margins due to heavy discounts.

3. **Returns Analysis:**
   - Furniture and Technology items have higher return rates, indicating areas for quality or delivery improvements.

4. **Seasonality:**
   - Monthly sales trends reveal seasonal spikes, potentially driven by holidays or promotions.
  
   
<img width="1330" alt="image" src="https://github.com/user-attachments/assets/fc769f23-fb5e-43d0-aed6-2fef9b040703" />

---

## Enhancements for Future Versions

1. **Dynamic Data Connection:**
   - Integrate real-time sales data for continuous updates.
2. **Advanced KPIs:**
   - Include metrics like customer acquisition cost, lifetime value, and sales per region.
3. **Predictive Analytics:**
   - Leverage Tableau's built-in forecasting tools to predict future sales trends.
4. **Customization:**
   - Add user-specific filters for deeper insights into product categories and customer segments.

---

## Project Requirements
- **Software:** Tableau Desktop
- **Data Source:** Sample - Superstore (Excel file)

---
