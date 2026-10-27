# Finance Transaction Analysis - Power BI Dashboard

## 📌 Project Summary
Developed an end-to-end Power BI dashboard to analyze **12,000+ financial transactions** worth **$92.28M revenue**, covering 500 customers and 50 products. The dashboard provides actionable insights for sales, finance, and business strategy teams.

## 🎯 Business Problem
- Which customer segment and product drives maximum revenue?
- Which regions and sales channels are most profitable?
- How to track transaction status and mitigate failed payments?

## 🧹 Data Preparation & Transformation
- Cleaned raw dataset using **Power Query**: Removed duplicates, handled null values, standardized country/segment fields.
- Created calculated columns: Revenue Category, Transaction Status Flag.
- Built **DAX Measures**:
    - `Total Revenue = SUM(Transaction_Amount)`
    - `Transaction Count = COUNT(Transaction_ID)`
    - `Avg Revenue per Customer = DIVIDE([Total Revenue], [Total Customers])`

## 📊 Dashboard Features
**1. Executive Overview (Home Page):**
- KPIs: 12K Transactions, 92.28M Revenue, 500 Customers, 50 Products
- Slicers: Sales Channel, Customer Segment, Quantity, Month - for dynamic filtering

**2. Revenue Analysis:**
- Segment-wise Revenue (SMB: 34M - Top Performer)
- Product-wise Performance & Country-wise Revenue Distribution
- Channel-wise Transaction Trend

**3. Operational Insights:**
- Summary of Transaction Status, Failed vs Completed
- Deep-dive into top products and low-performing areas

## 💡 Key Business Insights
- **SMB segment contributes 37% of total revenue ($34M)** - Recommend to increase focus on SMB retention strategies.
- **USA market leads** in transaction volume - Potential for expansion in other regions.
- **Identified 15% failed transactions** - Scope for improving payment gateway reliability.

## 🛠️ Tech Stack
- Power BI Desktop, Power Query, DAX, Data Modeling, Excel
- Skills: Data Cleaning, Data Visualization, Business Intelligence, Stakeholder Reporting

## 📂 How to Run
1. Download `Finance_Transaction_Dashboard.pbix`
2. Open in Power BI Desktop (Latest Version)
3. No external dataset needed - Data is embedded.

## 👩‍💻 Author
**Deepika J** | Aspiring Data Analyst
- Seeking Full-time opportunity in Data Analytics / Business Intelligence
- LinkedIn: https://www.linkedin.com/in/deepikaajanakiraman | GitHub: deepika672006-sudo

---
*This project demonstrates my ability to convert raw financial data into strategic business decisions, aligning with BI Analyst / Data Analyst roles.*
