# Energy Consumption Forecasting Pipeline

## Project Overview
This project implements an end-to-end ETL pipeline for processing energy consumption data using Azure Data Factory, Azure Data Lake Storage Gen2, Azure Databricks, and Delta Lake. The pipeline ingests CSV files, converts them into Parquet format, processes them through Bronze, Silver, and Gold layers, and prepares the data for reporting and forecasting.

## Tech Stack
- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks
- Apache Spark (PySpark)
- Delta Lake
- GitHub

## Project Architecture

CSV Files
↓
Azure Data Factory
↓
Parquet Files
↓
Bronze Layer
↓
Silver Layer
↓
Gold Layer
↓
Power BI / Forecasting

## Bronze Layer
- Incremental Loading
- Watermarking
- Schema Evolution
- Data Validation
- Audit Logging
- Error Handling

## Silver Layer
- Data Cleaning
- Remove Duplicates
- Standardize Data Types
- Business Transformations

## Gold Layer
- Business Aggregations
- Forecast Dataset
- Reporting Tables

## Project Structure

Architecture/
Dashboards/
DataSets/
Development/
Testing/

## Author

Umamaheswari
