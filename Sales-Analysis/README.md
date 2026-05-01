# 📊 Retail Sales Performance Dashboard | Business Intelligence

## 📌 Project Overview
This project presents an interactive Power BI dashboard meticulously designed to analyze the sales and profitability of a retail superstore. The dashboard provides end-to-end insights into key business metrics, identifying trends across sales, profit, and quantity sold across multiple dimensions like product categories, regions, and customer segments.

---

## 🎯 Technical Workflow & DAX Engineering
As a **PL-300 Certified Data Analyst**, I implemented a rigorous BI lifecycle for this project:

*   **ETL & Power Query**: Extracted and transformed raw transactional data, handling date formats and creating time-based dimensions (Year, Month, Quarter) for granular analysis.
*   **Data Modeling**: Established a robust **Star Schema** with optimized **Many-to-One relationships** to ensure data integrity and report performance.
*   **DAX Implementation**: Engineered complex measures for Key Performance Indicators (KPIs):
    *   `Total Sales = SUM(Sales[Amount])`
    *   `Total Profit = SUM(Sales[Profit])`
    *   `Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)`

---

## 📈 Key Features & Interactivity
The dashboard offers a dynamic user experience for stakeholders:
*   **Executive KPIs**: High-level summary cards for **Total Sales**, **Total Profit**, and **Quantity Sold**.
*   **Trend Intelligence**: Line charts illustrating Month-over-Month (MoM) and Year-over-Year (YoY) performance.
*   **Geographical Drill-down**: Interactive maps showing sales distribution across **Regions** and **States**.
*   **Operational Analysis**: Ship mode and customer segment breakdown to identify logistics efficiency.
*   **Dynamic Filtering**: Integrated slicers for **Order Date**, **Region**, and **Category** for on-the-fly data exploration.

---

## 💡 Strategic Business Insights
*   **Seasonality**: Identified peak sales periods in **Q4**, suggesting the need for inventory ramp-up during year-end.
*   **Category Drivers**: Discovered that the **Technology** category drives the highest revenue, while **Office Supplies** maintains the most consistent margins.
*   **Regional Strength**: The **West Region** consistently outperforms others, pinpointing a high-growth market for targeted marketing.
*   **Logistics Trends**: Observed a correlation between 'Standard Class' shipping and high-volume orders from the 'Consumer' segment.

---

## 🗂️ Folder Contents
*   📄 **`Retail_Sales_Dashboard.pbix`**: The master Power BI file with full data model and DAX measures.
*   📂 **`Screenshots/`**: Visual snapshots of the dashboard pages.
*   🔗 **'dataset is inbuilt in pbix file'**

---

## ✅ Professional Summary
This project showcases my ability to bridge the gap between raw data and executive decision-making using **Microsoft Power BI**. It highlights my proficiency in **DAX engineering**, **Data Modeling**, and **Visual Storytelling**.

---
**Author**: Nishanth M | Microsoft Certified: PL-300 & DP-600 (Score: 920/1000).
