# 📊 Superstore Sales Dashboard
An intermediate-level Power BI dashboard built using 
the Kaggle Superstore dataset (9,800 rows).

## 🔗 Dashboard File
Download the .pbix file above to explore 
the interactive dashboard in Power BI Desktop.

## 📸 Screenshots

### Page 1 — Executive Summary
![Executive Summary](screenshots/page1_executive_summary.png)

### Page 2 — Regional Analysis
![Regional Analysis](screenshots/page2_regional_analysis.png)

### Page 3 — Product Performance
![Product Performance](screenshots/page3_product_performance.png)

## 🛠️ Tools Used
- Power BI Desktop
- Power Query (ETL)
- DAX (24 measures)
- Kaggle Superstore Dataset

## 📁 Data Model
- Star schema with 6 tables
- 5 active relationships
- 1 disconnected table (Sales Targets)

## 📐 DAX Measures Built
- Base KPIs: Total Sales, Profit, Orders, AOV
- Time Intelligence: YTD, MTD, QTD, LY
- Growth: YoY%, MoM%, Running Total
- Ranking: RANKX, Top N, Top 10 filter
- Advanced: Moving Avg, % of Total, Dynamic labels

## 💡 Key Features
- 3 drilldown hierarchies (Date, Category, Location)
- Cross-filtering between all visuals
- Conditional formatting with DAX color measures
- Interactive slicers (Date, Region, Segment, Category)
- Map visual with US city bubbles
