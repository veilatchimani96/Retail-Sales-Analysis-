# 🛒 Retail Sales Analysis Dashboard

## 📌 Project Overview
This project analyzes a retail sales dataset (Sep 2023 – Aug 2025) using Excel and Power BI to generate actionable business insights through data cleaning, transformation, and interactive dashboards.

## 🎯 Objectives
- Identify top-performing categories & sub-categories
- Analyze regional and customer sales distribution
- Examine payment method preferences
- Track monthly sales & profit trends
- Build an interactive dashboard for reporting

## 🧹 Data Preparation (Excel)
- Cleaned missing values in Unit Price, Cost, Quantity, Discount
- Merged customer names using `CONCATENATE`
- Filled blanks using `AVERAGEIF` (sub-category level)
- Created calculated fields:
  - **Sales** = Unit Price × Quantity  
  - **Cost** = Cost Price × Quantity  
  - **Profit** = Sales − Cost  

## 📊 Power BI Implementation
### Data Modeling
- Imported cleaned Excel dataset
- Applied transformations in Power Query
- Standardized data types & column names

### DAX Measures
- **Transaction Count** = COUNT(TransactionID)
- **Total Sales** = SUM(Sales Amount)
- **Profit Margin %** = DIVIDE(Profit, Sales)
- **Store Count** = DISTINCTCOUNT(Store Name)

## 📈 Dashboard Visuals
- Donut Chart → Sales by Category  
- Line Chart → Monthly Sales Trend  
- Column Chart → Sales by Region  
- Bar Chart → Profit by Sub-category  
- Donut Chart → Payment Methods  
- Area Chart → Profit Margin by Category  
- Column Chart → Sales by Gender  

## 🔍 Key Insights
- 💰 Total Sales: ₹16.5M | Profit: ₹5.3M | ~5,000 Transactions  
- 📍 East region leads; West underperforms  
- 👕 Fashion category drives highest sales  
- 📱 Smartphones generate highest profit  
- 👨 Male customers contribute more sales  
- 💳 Credit Cards & Cash dominate payments  
- 📈 Seasonal trends observed mid-year peaks  

## 🚀 Conclusion
The business shows strong performance with growth opportunities in underperforming regions, low-profit products, and digital payment adoption.

## 🛠 Tools Used
- Microsoft Excel  
- Power BI Desktop  

