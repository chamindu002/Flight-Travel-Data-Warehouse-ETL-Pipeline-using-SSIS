# Flight-Travel-Data-Warehouse-ETL-Pipeline-using-SSIS


Designed and implemented a complete ETL pipeline and data warehouse solution for a flight travel dataset using Microsoft SQL Server and SSIS. Extracted data from multiple sources (CSV and SQL), performed data cleansing, transformation (e.g., NULL handling, derived columns, joins), and loaded it into a dimensional star schema warehouse with Slowly Changing Dimensions (SCD Types 1 & 2).
Key components included:

Used SSIS for data extraction, transformation, and loading into staging and data warehouse layers

Created dimension tables for flights, customers, journeys, baggage, tickets, and performance data

Built a central Fact_Travel fact table

Implemented stored procedures and SCD logic for historical tracking

Integrated with SSAS for cube creation and Power BI for data visualization and reporting

Tools Used: SQL Server, SSIS, SSAS, Power BI
