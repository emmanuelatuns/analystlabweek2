# 📊 ABC Retail Company - Sales Performance Dashboard

## AnalystLab Africa - Week 2 Business Intelligence Assignment

---

## 📌 Project Overview

This project involves building an **interactive executive dashboard** for a national retail company using **Microsoft Power BI**. The dashboard enables management to monitor sales performance, profitability, customer behavior, and regional performance through interactive visualizations and key performance indicators (KPIs).

**The Challenge:**
- No single source of truth for business metrics
- Difficulty identifying best and worst performing segments
- Inability to track sales trends over time
- Reactive rather than proactive decision-making

**The Solution:**
An interactive Power BI dashboard that transforms raw sales data into meaningful insights for strategic decision-making.

---

## 📁 Dataset

**Source:** [Superstore Sales Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

**Description:**
- **Total Records:** 9,994 orders
- **Time Period:** 2015-2018
- **Geography:** 4 US regions (West, East, Central, South)
- **Products:** Furniture, Office Supplies, Technology
- **Customer Segments:** Consumer, Corporate, Home Office

**Key Columns:**

| Category | Columns |
|----------|---------|
| **Order Info** | Order ID, Order Date, Ship Date, Ship Mode |
| **Customer** | Customer ID, Customer Name, Segment |
| **Location** | Country, City, State, Postal Code, Region |
| **Product** | Product ID, Category, Sub-Category, Product Name |
| **Financial** | Sales, Quantity, Discount, Profit |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Microsoft Power BI** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX (Data Analysis Expressions)** | Creating calculated measures |
| **Superstore Dataset** | Source data for analysis |

---

## 📊 Dashboard Features

### 5 Key Performance Indicators (KPIs)

| KPI | Value | Calculation |
|-----|-------|-------------|
| **Total Sales** | $2.3M | SUM(Sales) |
| **Total Profit** | $286K | SUM(Profit) |
| **Total Orders** | 9,994 | COUNT(Order ID) |
| **Average Sales** | $230 | AVERAGE(Sales) |
| **Profit Margin** | 12.4% | DIVIDE(SUM(Profit), SUM(Sales)) |

### 8+ Interactive Visualizations

| Visual | Purpose |
|--------|---------|
| 1. Bar Chart | Sales by Region |
| 2. Bar Chart | Top 10 Products by Profit |
| 3. Column Chart | Sales by Category |
| 4. Column Chart | Profit by Customer Segment |
| 5. Line Chart | Monthly Sales Trend |
| 6. Donut Chart | Sales Distribution by Category |
| 7. Map | Sales by State |
| 8. Matrix Table | Segment, Region, Category Performance |

### Interactive Slicers

| Slicer | Purpose |
|--------|---------|
| Region | Filter by West, East, Central, South |
| Category | Filter by Furniture, Office Supplies, Technology |
| Date Range | Filter by Order Date |

---

## 📈 Key Insights

### 5 Key Business Insights

| # | Insight | Evidence |
|---|---------|----------|
| 1 | **Western region drives highest sales** (31% of total) | Sales by Region chart |
| 2 | **Technology category most profitable** (18% margin) | Category performance analysis |
| 3 | **Consumer segment largest revenue driver** (45% of sales) | Segment performance analysis |
| 4 | **Q4 shows strong seasonal peaks** (40% above Q1) | Monthly trend analysis |
| 5 | **Corporate segment has highest margins** (15.2%) | Matrix table analysis |

### 3 Business Risks

1. **Over-reliance on Western region** - 31% of total sales concentrated in one region
2. **Low Furniture profitability** - 9.8% margin vs 12.4% company average
3. **Seasonal revenue vulnerability** - 40% of annual sales in Q4

### 3 Business Opportunities

1. **Expand into South region** - Only 55% of Western region performance
2. **Bundle technology products** - Highest margin category
3. **Grow B2B corporate segment** - Highest profit margins (15.2%)

---

## 💡 Recommendations

### 5 Actionable Recommendations

| # | Recommendation | Expected Impact | Timeline |
|---|----------------|-----------------|----------|
| 1 | **Expand Western Region Strategies Nationwide** | 10-15% sales increase | 3-6 months |
| 2 | **Focus Marketing on Technology Category** | 15% tech sales increase | 2-4 months |
| 3 | **Implement Consumer Loyalty Program** | $200K annual revenue | 3 months |
| 4 | **Optimize Q4 Inventory & Marketing** | 15% Q4 sales increase | Annual cycle |
| 5 | **Develop B2B Corporate Sales Team** | $175K annual profit | 4-6 months |

**Total Expected Benefit:** ~$1M+ in additional annual revenue/profit

---

## 📁 Repository Structure
