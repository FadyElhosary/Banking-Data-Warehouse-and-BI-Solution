 Bank Data Warehouse Project

 Overview
This project aims to transform transactional banking data from an OLTP system into an OLAP-based Data Warehouse.
The ETL process is implemented using **SSIS**,
analytical cubes are created with **SSAS**
reports are generated using **SSRS**,
and interactive dashboards are built in **Power BI**.

## Technologies Used
- **Microsoft SQL Server** (Database Management System)
- **SSIS** (SQL Server Integration Services) - ETL Process
- **SSAS** (SQL Server Analysis Services) - OLAP Cubes
- **SSRS** (SQL Server Reporting Services) - Reports
- **Power BI** - Data Visualization
- **Galaxy Schema** with Fact & Dimension Tables

## Data Warehouse Schema
The data warehouse follows a **Galaxy Schema** structure with:
- **Fact Tables**: Transactions, Loans
- **Dimension Tables**: Customers, Accounts, Time, Branches, Products, etc.

##  Setup & Usage
1. **Load Data**: Run the **SSIS package** to extract, transform, and load data from OLTP to OLAP.
2. **Process OLAP Cubes**: Use **SSAS** to build and deploy cubes for analysis.
3. **Generate Reports**: View predefined reports using **SSRS**.
4. **Visualize Data**: Open Power BI dashboards to interact with insights.


## 📩 Contact
- **Email**: fadymohamed1@gmail.com  
- **LinkedIn**: [https://www.linkedin.com/in/fady-elhosary-68064a338/]  

