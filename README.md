# Denis Project in Microsoft-Fabric

<h2> 📌 Project Overview </h2>

This project implements a centralized data warehousing solution using Microsoft Fabric Lakehouse architecture. It integrates sales-related data from multiple sources and transforms it into a curated model ready for reporting and analytics.

The solution follows the Medallion Architecture (Bronze → Silver → Gold) to ensure scalability, data quality, and business-ready insights.

<h2> 🎯 Project Objective </h2>

Build a centralized data warehouse in Microsoft Fabric to:

Integrate sales data from multiple sources (Flat files, Excel, CSV, JSON)

Clean, transform, and standardize raw data

Create a single business-ready dataset

Enable reporting and analytical insights

<h2> 🏗 Architecture Overview</h2>

![Healthcare Architecture](Denis-architecture.png)

<h2>🔹 Bronze Layer (Raw Data)</h2>

<h3> Purpose: </h3> Store raw ingested data without transformation.

<h3>Data Sources:</h3>

Sales.csv

Products.xlsx

Customers.json

Geography.json

Categories.csv

Subcategories.csv

<h3>Key Features:</h3>

Maintains original structure

Enables traceability and auditing

Supports reprocessing
