
# End-To-End Business Intelligence Solution
## Overview

This repository contains the source code and documentation for the Business Intelligence (BI) solution developed as part of the Experis Academy BI Developer Bootcamp. The focus of this project is on creating a robust BI solution for analyzing sales data.
The project involves the development of an ETL process, a Data Warehouse, a Power BI data model, and the implementation of reports and dashboards.


## Project Goals:

Data Mart:
Create a Data Mart for the company's sales department, encapsulating summarized data on company sales, along with detailed information on products, product categories, customers, branches, and salespeople.

Dashboard and Reports:
Develop an interactive and informative dashboard with Key Performance Indicators (KPIs) to empower the sales department with data-driven insights for effective decision-making

## Project Structure:
1. ETL Process:
Technologies:
SSIS (SQL Server Integration Services)
Directory: etl/
The etl/ directory contains scripts and configurations for the Extract, Transform, Load (ETL) process. This process extracts data from the operational database, transforms it according to the Data Mart schema, and loads it into the Data Mart.

2. Data Warehouse:
Directory: data_warehouse/
Description: Holds the schema and scripts for the Data Warehouse. This is where the summarized sales data is organized for efficient querying and reporting.

3. Power BI Model:
Directory: power_bi_model/
Description: Contains the Power BI data model. This model defines relationships, measures, and calculated fields to enable insightful analysis within Power BI.

4. Reports and Dashboards:
Technologies: Power BI
Directory: reports_dashboards/
Description: Implementation of reports and dashboards using Power BI. Visualizations are designed to provide a clear overview of sales performance and key metrics.

Sales Dashboard:
The Sales Dashboard provides a visually appealing representation of key performance indicators (KPIs) and insights. It enables quick decision-making and a comprehensive view of sales performance.

Salespeople Report:
The Salespeople Report offers detailed metrics and information on individual salespeople. It aids in understanding their contributions to overall sales and identifies areas for improvement.

Customer Report:
The Customer Report displays information and metrics related to customers, providing valuable insights for targeted marketing and enhanced customer relationship management.

5. Documentation:
Directory: docs/
Description: Contains detailed design documents, ERD, and any other documentation related to the BI solution.








