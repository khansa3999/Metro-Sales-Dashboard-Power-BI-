# 📊 Metro Business Performance Dashboard

A fully developed Business Intelligence dashboard designed to monitor sales performance, optimize operations, and enable customer segmentation using RFM analysis.

---

## 📌 Overview

The **Metro Business Performance Dashboard** provides interactive insights into:

- Sales & Profitability
- Operational Efficiency
- Employee Performance
- Customer Behavior & Segmentation

The solution is built using a **Star Schema Data Model** to ensure scalability, performance, and analytical accuracy.

---

## 🎯 Objectives

- Monitor overall business performance
- Identify sales trends and seasonality
- Analyze product and city-level revenue
- Optimize workforce scheduling
- Segment customers using RFM strategy
- Enable data-driven decision-making

---

## 🏗 Data Model Architecture

The dashboard follows a **Star Schema** structure.

### 🔹 Fact Table
- `FactSales`

### 🔹 Dimension Tables
- `DimDate`
- `DimCustomer`
- `DimProduct`
- `DimEmp`

This model supports efficient DAX measures and interactive filtering.

---

## 📈 Dashboard Structure

### 1️⃣ Sales Overview

**Focus:** Financial performance and trend analysis

**Key Visuals:**
- KPI Cards (Total Sales, Profit, AOV)
- Sales Trend (Line Chart)
- Top 10 Products by Revenue
- Sales by City (Map)

**Insights Delivered:**
- Revenue growth tracking
- Seasonal trend identification
- High-performing product analysis
- Geographic revenue distribution

---

### 2️⃣ Operational Optimization

**Focus:** Resource and performance management

**Key Visuals:**
- Sales by Hour and Day
- Employee Performance Table
- Sales by Gender
- Interactive slicers (City, Employee, Gender)

**Insights Delivered:**
- Peak business hours
- Staff productivity tracking
- Workforce optimization opportunities

---

### 3️⃣ Customer Segmentation (RFM Analysis)

**Focus:** Customer behavior and retention strategy

**RFM Metrics Implemented:**
- Recency
- Frequency
- Monetary Value

**Key Visuals:**
- Customer Segmentation by Visits
- Monetary vs Frequency Scatter Plot
- Age & Gender Distribution
- RFM KPI Cards

**Insights Delivered:**
- Loyal vs At-Risk customers
- High-value customer identification
- Targeted marketing opportunities

---

## 🧮 Key KPIs

- Total Sales
- Total Profit
- Average Order Value (AOV)
- Sales by Product
- Sales by City
- Employee Performance Metrics
- Customer RFM Metrics

---

## ⚠ Data Integrity Notes

During development, a foreign key mismatch was identified between `FactSales` and some dimension tables, causing `(Blank)` categories in certain visuals.

**Recommended Action:**
- Clean data in Power Query
- Validate foreign key relationships
- Introduce default dimension records if needed

---

## 🛠 Tools & Technologies

- Microsoft Power BI
- DAX (Data Analysis Expressions)
- Power Query
- Star Schema Data Modeling
- RFM Segmentation Strategy

---

## 🚀 How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Refresh data (if applicable).
3. Use slicers to filter by:
   - Date
   - City
   - Employee
   - Gender
4. Navigate between report pages.

---

## 📊 Business Impact

This dashboard enables:

- Faster executive reporting
- Improved operational planning
- Enhanced customer targeting
- Performance benchmarking
- Data-driven strategic decisions

---

## 🔮 Future Enhancements

- Year-over-Year comparisons
- Forecasting models
- Drill-through pages
- Power BI Service deployment with scheduled refresh
- Automated data validation checks

---

## 👩‍💼 Author

Business Intelligence & Data Analytics Project  
Metro Retail Performance Analytics Initiative  

---

⭐ If you found this project useful, consider giving it a star!
```
