# Auckland Housing Snowflake Analytics

## Project Overview
This project analyzes Auckland housing market trends using Snowflake and Power BI.

The goal is to build an end-to-end cloud analytics workflow including:
- Data ingestion
- SQL transformation
- Cloud warehousing
- Analytics reporting
- Business insights

## Tech Stack
- Snowflake
- SQL
- Power BI
- GitHub

## Current Progress
- Created Snowflake warehouse
- Created database and schema
- Loaded housing CSV data
- Built raw and cleaned tables
- Performed SQL datatype transformations

## Planned Enhancements
- Advanced SQL analytics
- Power BI integration
- Automated pipelines
- Regional trend analysis
- Rental yield insights

## Data Source

This project uses publicly available Auckland housing market reports from Barfoot & Thompson to explore regional sales trends, pricing patterns, and bedroom-level housing analytics.

## Data Preparation

Prior to loading data into Snowflake, Excel Power Query was used to prepare and transform the source datasets.

Key transformations included:

* Cleaning and standardizing source data
* Unpivoting monthly housing metrics into a relational structure
* Preparing datasets for Snowflake ingestion
* Exporting transformed datasets as CSV files

This preprocessing stage improved data quality and enabled efficient downstream analysis.

## Data Engineering Workflow

The project follows an end-to-end analytics workflow:

Barfoot & Thompson Housing Reports
→ Excel Power Query Transformation
→ CSV Data Preparation
→ Snowflake Data Ingestion
→ SQL Data Cleaning and Transformation
→ Data Modelling and Business Views
→ Power BI Reporting and Analysis

## Snowflake Implementation

Completed Snowflake development activities include:

* Warehouse creation and configuration
* Database and schema setup
* Raw data ingestion
* Data type standardization and cleansing
* Sales, rental, and volume dataset integration
* Suburb-to-region mapping
* Business reporting view creation
* Region-level housing analytics model development

## Key Business Questions

This project aims to answer the following business questions:

* Which Auckland regions have experienced the strongest housing price growth?
* How do rental prices compare with property sale prices across regions?
* Which regions generate the highest rental yield potential?
* How have housing sales volumes changed over time?
* What trends exist across different bedroom categories?
* How do housing market conditions vary across Auckland suburbs and regions?

## Development Approach

AI-assisted development tools, including Snowflake Cortex, were used to accelerate SQL development and data transformation workflows. All generated SQL was reviewed, tested, debugged, and validated to ensure accurate joins, correct business logic, and reliable analytical outputs.
