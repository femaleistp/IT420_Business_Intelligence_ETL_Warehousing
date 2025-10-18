# IT420: Business Intelligence and ETL Warehousing

**Author:** Brittany Hancock  
**Term:** Fall 2025  
**Instructor:** Lenore Montalbano  
**College:** Centralia College  

---

## Overview
This folder includes all four major projects for IT420: Data Warehousing and Business Intelligence.  
Each project builds on the last to show how raw data becomes clean, organized, and ready for analysis through ETL workflows.  
All work uses **SQL Server Integration Services (SSIS)** and **SQL Server Management Studio (SSMS)** to design and manage business-intelligence systems.

---

## Projects

### Project 1 – Data Audit Memo + Flat File Load
- Reviewed three messy client datasets using the **Data Audit Framework** (Source, Format, Quality, Risks).  
- Wrote a one-page professional memo explaining findings and recommendations.  
- Attempted imports into SQL Server, documented both successful loads and schema errors.  
- Learned how to communicate data-quality problems clearly to non-technical stakeholders.  

### Project 2 – ETL Package Deliverable
- Built an **SSIS package** to clean and standardize customer, product, and sales data.  
- Fixed missing or invalid values, standardized category names and states, and removed duplicates.  
- Produced three clean output files: `Customers_clean.csv`, `Products_clean.csv`, and `Sales_clean.csv`.  
- Saved the finished ETL package and cleaned files as part of the consulting portfolio.  

### Project 3 – Staging to Warehouse Deliverable
- Designed and implemented a **star schema warehouse** with `DimCustomer`, `DimProduct`, `DimDate`, and `FactSales` tables.  
- Extended the ETL package to load data from staging into warehouse tables with surrogate-key lookups.  
- Verified referential integrity and calculated totals for sales.  
- Documented the schema design in a consultant memo and ERD diagram.  

### Project 4 – OLTP vs OLAP Consulting Report
- Loaded expanded CSVs into both a **staging database (OLTP)** and a **warehouse (OLAP)**.  
- Compared query speed and results between the two systems using revenue-by-customer, region, and year reports.  
- Explained why OLAP warehouses are faster, safer, and more reliable for reporting.  
- Wrote a client-facing report (OLTP_vs_OLAP_Client_Consulting_Report.pdf) describing the risks of using OLTP for analysis and the benefits of OLAP for business decisions.

---

## Tools Used
- SQL Server Management Studio (SSMS)  
- SQL Server Integration Services (SSIS)  
- Visual Studio 2022  
- GitHub for version control  
- Microsoft Excel for CSV review  

---

## Folder Layout

Hancock_Brittany_IT420_Project_Solution/
│
├── Project1_DataAuditMemo/
├── Project2_ETLDeliverable/
├── Project3_StagingToWarehouse/
├── Project4_OLTPvsOLAP/
└── README.md

---

## Purpose
These projects show a complete end-to-end BI workflow:  
from messy client data to clean staging tables, from warehouse design to executive reporting.  
They demonstrate both technical ability and professional communication skills expected in real consulting work.

