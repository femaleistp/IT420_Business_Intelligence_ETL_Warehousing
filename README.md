# IT420: Business Intelligence and ETL Warehousing

**Author:** Brittany Hancock  
**Term:** Fall 2025  
**Instructor:** Lenore Montalbano  
**College:** Centralia College  

---

## Overview
This folder includes all major projects for IT420: Business Intelligence and ETL Warehousing.  
Each project builds on the last to show how raw data becomes clean, organized, and ready for analysis through ETL workflows, warehousing, reporting, and dashboarding.  
All work uses **SSIS**, **SSMS**, **SSRS**, and **Power BI** to design and deliver a full BI consulting solution.

---

## Projects

### Week 1 / Project 1 – Data Audit Memo + Flat File Load
- Reviewed three messy client datasets using the **Data Audit Framework** (Source, Format, Quality, Risks).  
- Wrote a one-page memo with findings and recommendations.  
- Attempted SQL Server imports and documented both successful loads and schema errors.  
- Established the starting point for all downstream cleaning and ETL work.

---

### Week 2 / Project 2 – ETL Package Deliverable
- Built an **SSIS ETL package** to clean and standardize customer, product, and sales data.  
- Fixed missing values, invalid formats, standardized categories and states, and removed duplicates.  
- Produced clean output files: `Customers_clean.csv`, `Products_clean.csv`, `Sales_clean.csv`.  
- Saved the ETL package and evidence as part of the consulting portfolio.

---

### Week 3 / Project 3 – Staging to Warehouse Deliverable
- Designed and implemented a **star schema warehouse** with `DimCustomer`, `DimProduct`, `DimDate`, and `FactSales`.  
- Extended the ETL process to load staging data into warehouse tables with surrogate-key lookups.  
- Validated referential integrity and confirmed correct sales totals.  
- Documented the schema in a consultant memo with ERD.

---

### Week 4 – OLTP vs OLAP Consulting Report
- Loaded expanded datasets into **staging (OLTP)** and the **warehouse (OLAP)**.  
- Compared query performance across customer and yearly totals using both systems.  
- Explained why OLAP is required for BI reporting and why OLTP is risky for analytics.  
- Delivered a client-facing report with evidence and recommendations.

---

### Week 5 – SSRS Executive Report Packet (Static)
- Created executive-ready static SSRS reports (tabular + chart).  
- Exported a combined PDF packet and saved `.rdl` files.  
- Wrote a brief reflection explaining how the reports support executive decision-making.

---

### Week 6 – SSRS Interactive Reports
- Built interactive SSRS reports with drill-downs and parameter filters.  
- Exported an interactive report packet and included source `.rdl` files.  
- Wrote a reflection identifying which interactive features add value and which could confuse users.

---

### Week 7 – Power BI Executive Dashboard (Baseline)
- Built a Power BI dashboard with a KPI card, chart, and slicer.  
- Used `DimSalesTarget` to calculate Actual vs Target.  
- Exported the layout to PDF and wrote a reflection describing dashboard design choices.

---

### Week 8 – Power BI Storytelling Dashboard
- Designed a storytelling dashboard using AdventureWorksDW2022 focused on **Product Mix**.  
- Added KPIs, trend visuals, detail charts, and an annotation/callout.  
- Exported a storytelling PDF and recorded a narrated walkthrough for executives.

---

### Week 9 – Multi-Page Executive Dashboard
- Expanded Week 8 into a complete multi-page executive decision-support system focused entirely on **Product Mix**.  
- Created a homepage with KPI cards and three supporting pages: **Product Mix Overview**, **Product Profitability**, and **Top Products Overview**.  
- Added page-navigation buttons, consistent formatting, and unified colors across all pages.  
- Wrote a one–two paragraph Executive Summary explaining the dashboard’s purpose and structure.  
- Exported the full dashboard packet and saved the `.pbix` file for the consulting portfolio.

---

### Week 10 – Predictive Insights Dashboard
- Built a Power BI predictive-insights dashboard using clustering, segmentation, and trend analysis.  
- Created new measures and visuals to identify high-performing products, at-risk segments, and forecast patterns.  
- Added executive-level insight statements that interpret the trends and patterns directly from the data.  
- Exported the dashboard as a PDF and saved the `.pbix` file and predictive-insights memo for the consulting portfolio.

---

## Tools Used
- SQL Server Management Studio (SSMS)  
- SQL Server Integration Services (SSIS)  
- Visual Studio 2022  
- SQL Server Reporting Services (SSRS)  
- Power BI Desktop  
- GitHub (version control)  
- Microsoft Excel  

---

## Folder Layout

Hancock_Brittany_IT420_Project_Solution/  
│  
├── Week1_DataAuditMemo/  
├── Week2_ETLDeliverable/  
├── Week3_StagingToWarehouse/  
├── Week4_OLTPvsOLAP/  
├── Week5_SSRSReports/  
├── Week6_InteractiveReports/  
├── Week7_Dashboard/  
├── Week8_StorytellingDashboard/  
├── Week9_ExecutiveDashboard/  
├── Week10_PredictiveInsights/  
└── README.md  

---

## Purpose
These projects show a full end-to-end BI workflow:  
from messy flat files to cleaned staging data, from warehouse design to SSRS reporting, and from storytelling dashboards to executive decision-support systems.  
This progression forms the foundation for the Capstone consulting portfolio and prepares for predictive insights in Week 10 and final handoff in Week 11.
