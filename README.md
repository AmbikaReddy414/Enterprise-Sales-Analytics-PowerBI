# 📊 Enterprise Sales Analytics Dashboard (Power BI)

## 🔍 Project Overview
This project presents an **end-to-end sales analytics solution** built using **Power BI**.  
The dashboard analyzes **sales performance, profitability, regional behavior, and product-level insights** using interactive and advanced visualizations.

The focus is not only on *what sells more*, but also on *what is more profitable* — a key concept in real business decision-making.

---

## 📁 Dataset Overview
The dataset contains transactional sales data with the following fields:

| Column | Description |
|------|------------|
| OrderDate | Date of transaction |
| Month | Month name |
| Region | Sales region |
| Category | Product category |
| SubCategory | Product / sub-category |
| Sales | Revenue amount |
| Profit | Profit earned |
| Quantity | Units sold |

### Data Preparation
- Sales and Profit stored as **decimal numbers**
- Quantity stored as **whole numbers**
- Data cleaned and validated in **Power Query**
- No DAX used — focus is on visual analytics

---

## 📄 Dashboard Pages

## 📄 Page 1 — Sales Overview

This page provides a **high-level understanding of business performance**.

---

### 1️⃣ Total Sales by Month (Clustered Bar Chart)
**Purpose:**  
Shows how sales are distributed across months.

**Why this chart:**  
Bar charts are ideal for **ranking and comparison**.

**Insights:**
- Identifies **peak sales months**
- Helps detect **seasonality**
- Highlights months with low performance

**Business Use:**  
Supports forecasting and planning decisions.

---

### 2️⃣ Sales Trend by Month (Line Chart)
**Purpose:**  
Visualizes how sales change over time.

**Why line chart:**  
Line charts are best for **trend analysis**.

**Insights:**
- Shows upward or downward trends
- Reveals fluctuations and stability
- Helps assess long-term performance

---

### 3️⃣ Total Sales by Category (Bar Chart)
**Purpose:**  
Compares sales contribution by product category.

**Insights:**
- Identifies the **highest-selling category**
- Shows which categories dominate revenue

**Key Learning:**  
High sales does not always mean high profit.

---

### 4️⃣ Total Sales by Region (Bar Chart)
**Purpose:**  
Analyzes geographic performance.

**Insights:**
- Identifies strongest and weakest regions
- Supports region-wise strategy and allocation

---

### 5️⃣ Total Sales KPI (Card)
**Purpose:**  
Displays overall sales value at a glance.

**Why this matters:**  
Executives need **instant numbers**, not charts.

---

### 6️⃣ Category Slicer
**Purpose:**  
Adds interactivity by filtering all visuals.

**Benefit:**  
Users can analyze performance for a **specific category** instantly.

---

## 📄 Page 2 — Advanced Analysis (Decision-Level Insights)

This page focuses on **diagnostic and strategic analysis**.

---

## 🔥 7️⃣ Sales vs Profit by Product (Scatter Chart)

### 🔍 MOST IMPORTANT ANALYSIS IN THIS PROJECT

**Purpose:**  
To understand the **relationship between Sales and Profit** at the product (Sub-Category) level.

**How to read this chart:**
- **Each dot = one Sub-Category**
- **X-axis → Sales**
- **Y-axis → Profit**
- **Color → Category**

---

### 📌 Interpretation Zones (Very Important)

#### ✅ Top-Right (High Sales, High Profit)
- Best-performing products
- Revenue drivers with strong margins

**Business Action:**  
👉 Invest more, promote aggressively

---

#### ⚠️ Bottom-Right (High Sales, Low Profit)
- Products sell a lot but make less money
- Indicates **pricing issues or high costs**

**Business Action:**  
👉 Review cost structure, renegotiate suppliers, revise pricing

---

#### 💡 Top-Left (Low Sales, High Profit)
- Niche but highly profitable products

**Business Action:**  
👉 Scale carefully, increase visibility

---

#### ❌ Bottom-Left (Low Sales, Low Profit)
- Weak products

**Business Action:**  
👉 Consider discontinuation or redesign

---

### ⭐ Why this chart is powerful
- Goes beyond totals
- Reveals **hidden risks**
- Shows that **sales alone is misleading**

This chart demonstrates **real business thinking**.

---

## 🔁 8️⃣ Sales and Profit Comparison by Category (Combo Chart)

**Purpose:**  
Compare **Sales volume vs Profit performance** together.

**Chart Design:**
- Columns → Sales
- Line → Profit (secondary axis)

**Key Insight:**
- A category may generate high sales but low profit
- Another category may generate lower sales but higher profit

**Example Insight:**
> Furniture may lead in sales, but Electronics may lead in profit.

**Business Value:**  
Supports margin-based decisions, not just revenue-based ones.

---

## 🏆 9️⃣ Top 10 Products by Sales (Bar Chart with Top-N Filter)

**Purpose:**  
Identify the **most important revenue-driving products**.

**How it works:**
- Top-N filter applied on SubCategory
- Ranked dynamically by Sales

**Insights:**
- Revenue concentration
- Helps focus on high-impact products

---

## 🌍 10️⃣ Top 10 Products per Region (Using Slicer)

**Purpose:**  
Understand regional product preferences.

**How it works:**
- Region slicer dynamically updates Top 10 products
- No DAX required

**Why this matters:**
- Different regions sell different products
- Enables region-specific strategies

---

## 🧠 Key Business Insights Summary
- High sales does NOT always mean high profit
- Profitability varies significantly across products and categories
- Revenue is concentrated in a small number of products
- Regional performance differs and requires tailored strategies

---

## 🛠 Tools Used
- Power BI Desktop
- Microsoft Excel
- GitHub

---

## 🚀 Final Note
This project demonstrates:
- Strong understanding of **visual selection**
- Ability to perform **diagnostic analysis**
- Business-oriented thinking without complex DAX

Author - Ambika Reddy

