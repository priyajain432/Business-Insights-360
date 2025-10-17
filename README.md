# 📊 AtliQ Hardware - Business Insights 360

# Live PowerBi Dashboard Link:
https://app.powerbi.com/view?r=eyJrIjoiMzYxOWY4MTQtODBmNC00NzdiLTliNTctYmNkMWY3MmM5NDY5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

## 🎯 Project Overview
AtliQ Hardware is experiencing rapid growth and has decided to implement Power BI analytics to make data-driven decisions and surpass competitors. This comprehensive dashboard provides insights across finance, sales, marketing, and supply chain operations.

## 🌐 Company Background
AtliQ Hardware is a global computer and accessories retailer operating through:
- 🏬 **Retailers** - Physical store partnerships
- 🎯 **Direct** - Company-owned sales channels
- 🚚 **Distributors** - Wholesale distribution network

**Business Challenge**: Faced significant losses from US market expansion due to:
- 📉 Reliance on intuition/excel analysis
- 🏆 Competitors' advanced analytics capabilities
- 🌍 Lack of data-driven global expansion strategy

## 🛠️ Tech Stack
- **🔍 SQL** - Data querying and exploration
- **💻 Power BI Desktop** - Dashboard development
- **📊 Excel** - Preliminary data processing
- **🧮 DAX Language** - Advanced measures and calculations
- **⚡ DAX Studio** - Query performance optimization
- **🔄 Power BI Gateway** - Automated data refresh

## 🚀 Key Features Implemented
✅ End-to-end data analytics solution  
✅ Interactive dashboards with drill-down capabilities  
✅ Automated data refresh (15-min intervals)  
✅ Cross-departmental KPI tracking  
✅ Supply chain optimization insights  
✅ Mobile-responsive design  

## ⚙️ Power BI Techniques Applied
- 🧩 Star Schema data modeling
- 📈 Advanced DAX measures (YTD, QTD, YoY%)
- 🎨 Dynamic visualizations with bookmarks
- 📅 Custom date tables (Fiscal calendar)
- 🔴🟢 KPI indicators with conditional formatting
- ⚡ Performance optimization (VertiPaq analyzer)
- ☁️ Power BI service deployment

## 💼 Business Concepts Covered
- 💰 Gross vs. net price analysis
- 🧾 Pre/Post-invoice deductions
- � Cost of Goods Sold (COGS) breakdown
- 📆 Time intelligence metrics (YTD, YTG, QoQ)
- 📊 Channel performance (Retailer/Direct/Distributor)
- 🌍 Market penetration analysis

---

## ❓ Project Kickoff Questions

### 🏗️ Project Fundamentals
1. **🎯 Objective**: Build decision-support system for global operations  
2. **📏 Success Metrics**: 20% reduction in expansion failures, 15% cost savings  
3. **⏳ Timeline**: 8-week delivery (2-week sprints)  
4. **👀 Stakeholder Review**: Bi-weekly demo sessions  

### 👥 Stakeholder Perspectives
5. **💡 Hopes**: Single source of truth for all business units  
6. **⚠️ Fears**: Data accuracy concerns, user adoption challenges  
7. **👨💻 User Needs**:  
   - C-level: Strategic overview  
   - Managers: Departmental deep-dives  
   - Analysts: Raw data access  

### 🔧 Requirements & Risks
8. **📝 Expectations**: 5 dashboards + training documentation  
9. **⚡ Risks**: Data latency, measure miscalculations  
10. **📦 Resources**: ERP data + Market intelligence feeds  
11. **🎨 Design**: Follow corporate branding guidelines  

---

## 🗃️ Dataset Understanding

### 📦 gdb041 Database

#### 🏷️ Dimension Tables
**🧑💼 dim_customer**  
- 🌍 27 markets (India, USA, Spain etc.)  
- 🤝 75 customers across:  
  - 🏢 Brick & Mortar (physical)  
  - 🛒 E-commerce (Amazon, Flipkart)  
- 📊 Sales channels: Retailer/Direct/Distributor  

**🗺️ dim_market**  
- 7 sub-zones → 4 regions (APAC/EU/LATAM)  

**📦 dim_product**  
- 💻 P&A (PC/Notebook/Desktop)  
- 🔌 N&S (Networking/Storage)  
- 14 categories with variants  

#### 🔢 Fact Tables
**🔮 fact_forecast_monthly**  
- 📅 Month-start normalized dates  
- 🔍 Key metric: `forecast_quantity`  

**💰 fact_sales_monthly**  
- 🏷️ Key metric: `sold_quantity`  

### 💳 gdb056 Database (Financials)
- ✈️ freight_cost: Logistics by market×year  
- 💵 gross_price: Product pricing  
- 🏭 manufacturing_cost: Production costs  
- ➖ pre_invoice_deductions: Customer discounts  
- ➖ post_invoice_deductions: Payment adjustments

- ---

## 🏗️ Data Modeling
Data modeling serves as the basement of this report. A well-structured model is essential for performance and reliability. Poor data modeling can drastically reduce report efficiency. 

In this project, we follow the **Snowflake schema** to normalize data, reduce redundancy, and optimize performance.

---

## 🎨 Dashboard Design
Based on stakeholder mock-ups, the dashboard suite is cleanly designed, focusing on usability and interactivity. All key performance indicators (KPIs) are measured using DAX logic and conditional formatting.

The **Home View** acts as the landing page, providing buttons that navigate users to specific dashboard views:

### 🔹 Dashboard Views

### 🏠 Home Page
![Home Page](https://github.com/priyajain432/Business-Insights-360/blob/af7385e9ebc338bdfef738f142fa8ca1c538ca1a/Home%20Page.png?raw=true)

### 📈 Marketing View
![Marketing View](https://github.com/priyajain432/Business-Insights-360/blob/af7385e9ebc338bdfef738f142fa8ca1c538ca1a/Marketing%20View.png?raw=true)

### 📊 Sales View
![Sales View](https://github.com/priyajain432/Business-Insights-360/blob/af7385e9ebc338bdfef738f142fa8ca1c538ca1a/Sales%20View.png?raw=true)

## 📊 Finance View

![Finance View](https://github.com/priyajain432/Business-Insights-360/blob/af7385e9ebc338bdfef738f142fa8ca1c538ca1a/Finance%20View%20.png?raw=true)

## 🏭 Supply Chain View
![Supply Chain View](https://github.com/priyajain432/Business-Insights-360/blob/af7385e9ebc338bdfef738f142fa8ca1c538ca1a/Supply%20Chain%20View.png?raw=true)

## 📊 Executive View

![Alt Text](https://github.com/priyajain432/Business-Insights-360/blob/955807072e7dccb0e05b7f13b41b60c282ebef73/Executive%20View.png)
---

## ✅ Project Outcome
With this report, key business decisions are driven by data insights. From department-specific KPIs to overall company performance, the dashboards help answer many "why" questions that support strategic initiatives.

---
