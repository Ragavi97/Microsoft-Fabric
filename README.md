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
<ul>
<li>Sales.csv</li><li>Products.xlsx</li><li>Customers.json</li><li>Geography.json</li><li>Categories.csv</li><li>Subcategories.csv</li>
</ul>


<h3>Key Features:</h3>
<ul>
  <li>Maintains original structure</li><li>Enables traceability and auditing</li><li>Supports reprocessing
</li>
</ul>

<h2>🔹 Silver Layer (Cleaned & Standardized Data)</h2>

<h3>Purpose:</h3> 
<ul><li>Improve data quality and prepare it for modeling.</li></ul>

<h3>Transformations Applied:</h3>
<ul>
  <li>Data type standardization</li><li>Handling null values & duplicates</li><li>Data cleansing & formatting</li><li>Schema alignment</li>
</ul>

<h3>Output Tables:</h3>
<ul>
  <li>Cleaned Sales</li><li>Cleaned Products</li><li>Cleaned Customers</li><li>Geography</li><li>Categories & Subcategories</li>
</ul>

<h2>🔹 Gold Layer (Business-Ready Data)</h2>

<h3>Purpose:</h3> 
<ul>
  <li>Deliver curated datasets optimized for analytics and reporting.</li>
</ul>

<h3>Features:</h3>
<ul>
  <li>Denormalized tables</li><li>Business logic & calculations</li><li>Optimized for Power BI reporting</li>
</ul>

<h3>Output:</h3>
<ul>
  <li>Fact and dimension tables</li><li>Business metrics for decision-making</li>
</ul>

<h2>🔄 Data Flow</h2>
<ul>
  <li>Raw data ingested into Bronze layer</li><li>Data cleaned and standardized in Silver layer</li><li>Business logic applied to create Gold layer
</li><li>Gold layer feeds reporting and analytics
</li>
</ul>

<h2> 📊 Reporting & Analytics </h2>
The Gold layer supports reporting tools such as:
<ul>
<li>Power BI</li>

<li>Fabric Notebooks & SQL Endpoints</li>

<li>Dashboarding & KPI tracking</li>
  
</ul>


<h3>Key Insights Enabled:</h3>

Sales performance analysis
<ul>
  <li>Customer behavior insights</li>
  <li>Product & category trends</li>
  <li>Geographic sales distribution</li>
</ul>


<h2> 🛠 Technologies Used </h2>
<ul>
  <li>Microsoft Fabric</li><li>Lakehouse Architecture</li><li>Data Pipelines / Dataflows Gen2</li><li>Spark / Notebooks</li><li>Power BI</li>
</ul>




