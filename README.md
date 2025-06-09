# AtliQ Hardware - Business Insights 360

## Project Overview
AtliQ Hardware is experiencing rapid growth and has decided to implement Power BI analytics to make data-driven decisions and surpass competitors. This comprehensive dashboard provides insights across finance, sales, marketing, and supply chain operations.


## Tech Stack
- **SQL** - Data querying
- **Power BI Desktop** - Dashboard development
- **Excel** - Data processing
- **DAX Language** - Measures and calculations
- **DAX Studio** - Performance optimization

## Key Features Implemented
✅ End-to-end data analytics solution for AtliQ Hardware  
✅ Interactive dashboards with drill-down capabilities  
✅ Automated data refresh through Power BI gateway  
✅ Comprehensive financial and sales performance tracking  
✅ Supply chain optimization insights  

## Power BI Techniques Applied
- Data modeling using Star Schema approach
- Advanced DAX measures and calculations
- Dynamic visualizations with bookmarks
- Custom date tables using M language
- KPI indicators with conditional formatting
- Performance optimization with DAX Studio
- Power BI service deployment and app creation

## Business Concepts Covered
- Gross price vs net price analysis
- Pre-invoice and post-invoice deductions
- Cost of goods sold (COGS)
- Year-to-Date (YTD) and Year-to-Go (YTG) metrics
- Sales channel performance (Retailer/Direct/Distributor)

## Company’s back ground
AltiQ hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells, computer and computer accessories through three mediums/channel

- **Retailers**
- **Direct**
- **Distributors**

Recently the company has faced a unforeseen loss by opening store in America based on the surveys, intuition and some excel analysis and also the company’s competitors has handful of analytics team to perform analysis and make data driven decision. So, the AltiQ hardware has no other option other than building their analytics team for data driven insights and decisions in the future to survive better in the industry.

Project kick off session, where you should get clear of for what and why this project and all other questions you have with regards to the project.

## Project Kickoff Questions

Before beginning dashboard development, these critical questions were addressed:

### Project Fundamentals
1. **Objective**: What is the primary purpose of building this Power BI dashboard?
2. **Success Metrics**: How will we measure the project's success?
3. **Timeline**: What is the project deadline and key milestones?
4. **Stakeholder Review**: Will stakeholders expect previews before final release?

### Stakeholder Perspectives
5. **Hopes**: What outcomes are stakeholders hoping to achieve?
6. **Fears**: What concerns do stakeholders have about the dashboard?
7. **User Needs**: 
   - Who will use this dashboard? 
   - What decisions will it support?

### Requirements & Risks
8. **Expectations**: What deliverables are stakeholders expecting?
9. **Risk Assessment**: What could go wrong during development?
10. **Resource Needs**: What data and other resources are required?
11. **Design Inputs**: Do stakeholders have specific visualization preferences?

## Dataset Understanding

After project kickoff meetings, the data engineering team provided the following datasets:

### gdb041 Database

#### Dimension Tables
**dim_customer**  
- 27 markets (India, USA, Spain etc.)
- 75 customers across platforms:
  - Brick & Mortar (physical)
  - E-commerce (Amazon, Flipkart etc.)
- Sales channels: Retailer, Direct, Distributor

**dim_market**  
- Same 27 markets organized in:
  - 7 sub-zones
  - 4 regions (APAC, EU, LATAM, null)

**dim_product**  
- Divisions:
  - P&A (PC, Notebook, Desktop)
  - N&S (Networking, Storage)
- 14 categories with multiple variants

#### Fact Tables
**fact_forecast_monthly**  
- Monthly demand forecasts (denormalized)
- Key field: `forecast_quantity`
- Dates normalized to month-start

**fact_sales_monthly**  
- Actual sales data (mirrors forecast structure)
- Key field: `sold_quantity`

### gdb056 Database (Financials)
- **freight_cost**: Logistics by market×year
- **gross_price**: Product pricing
- **manufacturing_cost**: Production costs by product×year
- **pre_invoice_deductions**: Customer discounts
- **post_invoice_deductions**: Payment adjustments

## Data Model

*Snowflake schema design with optimized relationships*

## Dashboard Views
1. **Executive Overview** - High-level KPIs
2. **Finance View** - Profitability and cost analysis
3. **Sales View** - Revenue by region and product
4. **Marketing View** - Campaign effectiveness
5. **Supply Chain View** - Inventory and logistics


## Project Documentation

## Acknowledgements
This project was developed as part of the Codebasics Power BI course. Special thanks to the course instructors for their guidance.

---

**Note**: Some report elements are connected to live databases and may require credential setup to view complete functionality.
