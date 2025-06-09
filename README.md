# 📊 AtliQ Hardware - Business Insights 360

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
