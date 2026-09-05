# 📊 India E-Commerce Sales Intelligence Dashboard

## Power BI Business Intelligence Project

An interactive Power BI dashboard developed to analyze Indian e-commerce sales performance, profitability, customer behavior, regional performance, and sales targets.

---

## 🎯 Project Objective

The objective of this project was to build a self-service analytics dashboard that enables management to:

- Monitor sales and profit performance
- Compare actual sales against targets
- Analyze year-over-year growth
- Identify top-performing products and customers
- Understand customer segments and payment behavior
- Analyze regional and city-level performance
- Drill down into product and customer-level details

---

## 🛠️ Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Star Schema
- Time Intelligence
- Data Visualization

---

## 📁 Dataset

The project contains:

### Sales Data

- 5,000 transaction records
- 4 regions
- 10 categories
- 50 sub-categories
- 4,844 customers
- 20 cities

### Sales Target Data

Monthly regional sales targets used for actual-vs-target analysis.

---

## 🔄 Data Preparation

Power Query was used for:

- Data type conversion
- Data cleaning
- Duplicate checking
- Null-value validation
- Text standardization
- Data enrichment

---

## 🧩 Data Model

A star-schema approach was implemented using:

- Sales fact table
- Dedicated Date dimension
- Sales Target table
- Measures table

---

## 📐 DAX

18 DAX measures were developed for:

- Total Sales
- Total Profit
- Profit Margin
- Total Orders
- Total Quantity
- Total Target
- Target Achievement %
- Sales vs Target Gap
- YoY Growth
- QoQ Growth
- MTD
- QTD
- YTD
- 3-Month Moving Average
- Contribution %
- Product Sales Rank
- Last Purchase Date

---

## 📊 Dashboard Pages

### Executive Summary

Provides a high-level overview of sales, profit, margin, orders, and target achievement.

### Sales Performance

Analyzes monthly sales trends, regional performance, and actual-vs-target performance.

### Product Analytics

Analyzes top products, category profitability, sales distribution, and the relationship between quantity and profit.

### Customer Intelligence

Analyzes top customers, customer segments, payment methods, and regional customer behavior.

### Regional Analysis

Provides region-level, city-level, and geographic sales analysis.

### Insights & Recommendations

Summarizes the major business findings and recommendations.

### Drill-Through Pages

Provides detailed product and customer-level analysis.

### Tooltip Pages

Provides additional contextual information when hovering over dashboard visuals.

---

# 📈 Key Business Insights

| Metric | Result |
|---|---:|
| Total Sales | ₹53.37 Crore |
| Total Profit | ₹7.97 Crore |
| Profit Margin | 14.94% |
| Top Region | North – ₹14.36 Crore |
| Highest Margin Category | Furniture – 15.35% |
| Highest Sales Category | Home Decor – ₹5.72 Crore |
| Target Achievement | ~90.8% |
| Weakest Quarter | Q3 2025 – 83.3% |
| Quantity–Profit Correlation | ~0.50 |

---

# 🖼️ Dashboard Preview

## Executive Summary

![Executive Summary](Screenshots/1.%20Executive%20Summary.jpg)

## Sales Performance

![Sales Performance](Screenshots/2.%20Sales%20Performance.jpg)

## Product Analytics

![Product Analytics](Screenshots/4.%20Product%20Analytics.jpg)

## Customer Intelligence

![Customer Intelligence](Screenshots/3.%20Customer%20Intelligence.jpg)

## Regional Analysis

![Regional Analysis](Screenshots/5.%20Regional%20Analysis.jpg)

---

# 💡 Key Business Recommendation

The dashboard highlights the Q3 2025 target shortfall and recurring mid-year sales softness, particularly around June. These patterns can be investigated further for seasonal planning, target setting, and sales strategy optimization.

---

# 🚀 Future Improvements

- Add a proper Customer ID
- Implement sales forecasting
- Add RFM customer segmentation
- Analyze discount effectiveness
- Add predictive analytics

## 📁 Project Structure

```text
India-Ecommerce-Sales-Intelligence-Dashboard/
│
├── Data/
│   ├── Ecommerce_Sales_Data_2024_2025.csv
│   └── Sales_Target.csv
│
├── PowerBI/
│   └── India_Ecommerce_Sales_Intelligence_Dashboard.pbix
│
├── Screenshots/
│   ├── 1. Executive Summary.jpg
│   ├── 2. Sales Performance.jpg
│   ├── 3. Customer Intelligence.jpg
│   ├── 4. Product Analytics.jpg
│   └── 5. Regional Analysis.jpg
│
└── README.md
---

## 👤 Project

**India E-Commerce Sales Intelligence Dashboard**

Built using Power BI, Power Query and DAX.
