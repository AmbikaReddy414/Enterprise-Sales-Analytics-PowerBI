# Sales Analytics – Detailed Documentation

## 1. Data Overview
The dataset contains historical sales transactions with the following key fields:
- Order Date
- Region
- Category
- Sub-Category
- Sales
- Profit
- Quantity

Sales and Profit are treated as decimal values, while Quantity is stored as a whole number.

---

## 2. Data Cleaning Steps
- Verified data types for all columns
- Ensured Sales and Profit are decimal values
- Ensured Quantity is a whole number
- Removed unnecessary columns (if any)
- Checked for blank or invalid values

---

## 3. Page 1 – Sales Overview Analysis
This page provides a high-level overview of sales performance:
- Total Sales by Month: Identifies seasonality and peak months
- Sales by Category: Compares category-level performance
- Sales by Region: Highlights regional contribution
- Sales Trend Line: Shows monthly sales movement
- Total Sales KPI: Displays overall sales value
- Category slicer enables interactive filtering

---

## 4. Page 2 – Advanced Analysis
This page focuses on deeper insights:
- Sales vs Profit Scatter Plot: Identifies high-sales low-profit products
- Sales and Profit Combo Chart: Compares revenue vs profitability by category
- Top 10 Products by Sales: Highlights key revenue drivers
- Region slicer dynamically updates Top 10 products per region

---

## 5. Key Business Insights
- Electronics generates the highest profit despite not always having the highest sales
- Certain products show high sales but lower profitability
- Sales performance varies significantly by region
- Revenue is concentrated among a small number of products

---

## 6. Tools Used
- Power BI Desktop
- Microsoft Excel
- GitHub
