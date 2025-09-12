# 🛒 Strategic Superstore Sales & Profitability Dashboard

## 🌟 Project Overview
This project delivers a **Business Intelligence (BI) dashboard** built in **Microsoft Power BI**, using the widely adopted [Superstore dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final).  

The dashboard empowers senior management with **actionable insights** into sales, profitability, and customer behavior. It provides clarity on **market expansion opportunities**, **product portfolio optimization**, and **customer segmentation** strategies.  

The solution consists of three interconnected views:
- **Superstore Overview** – High-level KPIs and executive summary.  
- **Market Analysis** – Regional and sub-regional performance tracking.  
- **Product Analysis** – Sales and profitability across categories and sub-categories.  

---

## 🎯 Business Objectives
This dashboard addresses the most pressing questions for decision-makers:

1. **Which regions and sub-regions deliver the highest profitability and growth potential?**  
   - Identify areas with the strongest YoY growth vs. underperforming markets.  

2. **Which product categories and sub-categories are driving sales vs. profitability?**  
   - Evaluate whether discount-heavy categories erode margins.  

3. **Where are sales or profits lagging, and what are the contributing factors?**  
   - Pinpoint underperforming regions, customer segments, or products.  

4. **How are performance metrics trending over time?**  
   - Track YoY changes in sales and profitability to assess long-term momentum.  

---

## 📊 Key Performance Indicators (KPIs) & Analysis

| **KPI**                  | **Business Significance**                                                           | **Calculation / Definition**                                                                 |
|---------------------------|-------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| **Total Sales**           | Measures overall revenue generated across all transactions.                         | `SUM(Sales)`                                                                                 |
| **Total Profit**          | Assesses financial gains after costs are deducted.                                  | `SUM(Profit)`                                                                                |
| **Profit Margin %**       | Evaluates profitability efficiency by comparing profit to sales.                    | `(Total Profit ÷ Total Sales) × 100`                                                         |
| **YoY Sales Growth %**    | Tracks business momentum and highlights growth/decline patterns year-over-year.     | `((Sales Current Year - Sales Previous Year) ÷ Sales Previous Year) × 100`                   |
| **% Profit Lost**         | Shows inefficiency due to discounts or operational issues.                          | `(Profit Lost ÷ Total Potential Profit) × 100`                                               |
| **% Sales Lost**          | Highlights lost revenue opportunities (returns, stockouts, excessive discounts).    | `(Sales Lost ÷ Total Potential Sales) × 100`                                                 |

### Highlights
- **Executive Summary:** Quick snapshot of performance for senior leadership.  
- **Geographical Analysis:** Interactive maps to rank regions by profitability.  
- **Product Insights:** Clear view of categories (Technology, Furniture, Office Supplies) and sub-categories driving performance.  
- **Customer Segment Breakdown:** Compare **Consumer**, **Corporate**, and **Home Office** segments.  
- **Trend Analysis:** Multi-year sales and profit trends for long-term strategy.  

---

## ⚙️ Technical Execution

### **Data Source**
- Publicly available **Superstore dataset** (Kaggle).  
- Includes dimensions such as Sales, Profit, Region, Customer Segment, Category, and Sub-Category.  

### **Data Transformation (Power Query)**
- Cleaned and standardized raw data.  
- Handled missing values, corrected data types, and built calculated columns.  

### **Data Modeling**
- Implemented a **Star Schema** for efficiency and scalability.  
- Created clear relationships between fact tables (Sales) and dimensions (Customer, Product, Region).  

### **Advanced DAX Measures**
- Developed custom measures for KPIs like **% Profit Lost**, **% Sales Lost**, and **YoY Sales Growth**.  
- Leveraged **time intelligence** for rolling-year and period-over-period comparisons.  

### **Visualization & Interactivity**
- Designed dashboards with intuitive slicers (Region, Segment, Year).  
- Enabled drill-throughs for category → sub-category → product analysis.  
- Created executive-level summaries with both breadth and depth.  

---

## 📸 Screenshots

### 1. Superstore Overview
![Superstore Overview](Overview.png)

### 2. Market Analysis
![Market Analysis](MarketAnalysis.png)

### 3. Product Analysis
![Product Analysis](ProductAnalysis.png)

---

## 🔑 Key Learnings
- Converting raw transactional data into **executive-level insights**.  
- Building a **robust data model** that supports multiple levels of analysis.  
- Applying **advanced DAX** for profitability, discount impact, and YoY trend analysis.  
- Designing **C-suite ready dashboards** that combine clarity with interactivity.  

---

## 🛠️ Get Started
- This repository includes **static screenshots** (`Overview.png`, `MarketAnalysis.png`, `ProductAnalysis.png`) to showcase the dashboard.  
- The full Power BI project file (`.pbix`) is available upon request for recruiters or collaborators.  
- Explore the visuals to understand how data-driven dashboards can **transform retail strategy**.  

---
