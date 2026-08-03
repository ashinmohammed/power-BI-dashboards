# 🛒 Grocery Inventory Dashboard | Power BI

An interactive **Power BI dashboard** designed to analyze grocery inventory, sales performance, and supplier performance. The dashboard helps businesses monitor inventory levels, identify products below reorder level, analyze sales trends, and evaluate supplier performance through an intuitive three-page report.

The project demonstrates practical use of **Power Query**, **DAX**, **Field Parameters**, and **Page Navigation** to build an interactive business intelligence solution.

---

# 📷 Dashboard Preview

## 📌 Overview Dashboard

![Overview Dashboard](/images/grocery%201%20main%20page.png)

---

## 📈 Sales Performance Dashboard

![Sales Performance Dashboard](/images/grocery%202%20page.png)

---

## 🚚 Supplier Analysis Dashboard

![Supplier Analysis Dashboard](/images/grocery%203%20page.png)

---

# 📌 Project Overview

This dashboard consists of three interactive pages:

- 📦 Inventory Overview
- 💰 Sales Performance Analysis
- 🚚 Supplier Analysis

Users can easily navigate between pages using the built-in navigation menu located on the left side of every report page.

---

# 🚀 Dashboard Features

## 📦 Overview Dashboard

### KPIs

- Total Stock Quantity
- Total Stock Value
- Products Below Reorder Level
- Average Inventory Turnover Ratio

### Visualizations

- Monthly Stock Trend vs Reorder Level
- Category-wise Stock Comparison
- Inventory Status Distribution
- Product Inventory Details Table

### Key Insights

- The inventory contains **55,053 total units** with a total stock value of **$332.7K**.
- **455 products** are currently below their reorder level and require replenishment.
- Fruits & Vegetables maintain the highest inventory levels among all product categories.
- Inventory levels fluctuate throughout the year, with October showing one of the highest stock quantities.
- Active, Backordered, and Discontinued products are distributed almost evenly, indicating a balanced inventory status.
- A custom **Level Stock Status** DAX measure is added to table that classifies products into inventory status categories, making it easier to identify products requiring immediate attention.

---

# 💰 Sales Performance Dashboard

### KPIs

- Total Products
- Total Sales Volume
- Total Revenue

### Visualizations

- Sales by Category
- Sales by Product
- Revenue vs Sales Volume
- Sales Summary Table

### Interactive Features

- Field Parameters
    - Total Revenue
    - Total Sales Volume

Users can dynamically switch between both metrics without changing visuals.

### Key Insights

- The business generated approximately **$344.3K** in total revenue from **58,336 units sold**.
- Fruits & Vegetables generate the highest revenue among all categories.
- Arabia Coffee is the highest revenue-generating product.
- The Revenue vs Volume analysis shows that some categories generate high revenue without having the highest sales volume, indicating higher-value products.
- Dynamic field parameters allow users to compare revenue and sales volume across both category and product levels.

---

# 🚚 Supplier Analysis Dashboard

### KPIs

- Total Suppliers
- Products Below Reorder Level

### Visualizations

- Supplier Product Table
- Stock Quantity by Supplier
- Revenue by Supplier

### Interactive Features

- Field Parameters
    - Total Stock Quantity
    - Total Stock Value
    - Total Revenue
    - Total Sales Volume

### Key Insights

- The business works with **350 suppliers**.
- **455 products** remain below their reorder level, helping procurement teams prioritize restocking.
- Katz supplies the highest inventory quantity.
- Youfeed generates the highest revenue among all suppliers.
- Supplier performance can be analyzed dynamically by switching between stock, revenue, and sales metrics.

---
# 📚 What I Learned

This project helped me strengthen both my technical and dashboard design skills. Throughout the development process, I learned:

- 🧹 Cleaning and transforming raw data using **Power Query**
- 📐 Creating **DAX measures** to calculate KPIs and business metrics
- 📊 Using DAX to build a custom **Level Stock Status** measure for inventory analysis
- 🧭 Implementing **page navigation** to create a seamless multi-page reporting experience
- 🎛 Using **Field Parameters** to dynamically switch between different business metrics within the same visual
- 🎨 Applying **UI/UX design principles** to build a clean, user-friendly, and consistent dashboard layout
- 📈 Designing dashboards that not only visualize data but also support business decision-making through interactive reports

This project significantly improved my understanding of how to combine data modeling, visualization, and user experience to create professional Power BI dashboards.
## 📬 Feedback

Feedback and suggestions are always welcome!

If you found this project helpful, consider giving it a ⭐ on GitHub.