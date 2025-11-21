# Movie-Data-Engineering-Using-Databricks

## Overview

This project leverages Databricks Medallion Architecture to build an automated movie data pipeline. Raw CSV data is ingested into the Bronze layer, cleaned and transformed into the Silver layer, and aggregated into Gold layer views for analytics. These views power Databricks dashboards for visualization. A Databricks Job Pipeline automates the entire process, ensuring efficiency and scalability.

### THE OBJECTIVE

- Implement the Medallion Architecture in a Databricks environment.
- Understand data flow across Bronze, Silver, and Gold layers.
- Explore Databricks dashboard functionality for data visualization.
- Configure and schedule Databricks jobs to automate the pipeline and ensure smooth execution of data transformations.

## PROBLEM STATEMENT

Organizations often struggle to efficiently process and analyze large volumes of raw data for actionable insights. In this case, a CSV file containing movie reviews and ratings from Netflix and Amazon Prime, including IMDb and Rotten Tomatoes scores, needs to be transformed into a structured, analytics-ready format. The challenge is to:
- Ingest raw data into a Bronze layer Delta table while preserving its integrity.
- Implement the Medallion Architecture to progressively refine data through Silver and Gold layers.
- Create interactive dashboards from Gold layer views for visualization and insights.
- Automate the entire workflow by designing a Databricks Job Pipeline, ensuring scalability, reliability, and repeatability.

### PROJECT DELIVERABLES

Following is a complete list of all project deliverables:
<table>
<tr><th>DELIVERABLE</th>	<th>DESCRIPTION</th></tr>
<tr><td>Bronze Layer Delta Table</td><td>	Ingest raw CSV file containing movie reviews and ratings into a Delta table, preserving original data.</td></tr>
<tr><td>Silver Layer Transformation	</td><td>Clean and standardize data from Bronze layer, ensuring quality and consistency for analytics.</td></tr>
<tr><td>Gold Layer Views</td><td>	Create curated and aggregated views from Silver layer for reporting and visualization.</td></tr>
<tr><td>Databricks Dashboard </td><td>	Develop interactive dashboards using Gold layer views to visualize insights on movie ratings.</td></tr>
<tr><td>Job Pipeline Automation	</td><td>Design and configure a Databricks Job Pipeline to automate ingestion, transformation, and dashboard updates.</td></tr>
</table>

## GOALS VS DELIVERABLES
<table>
<tr><th>
PROJECT GOAL	</th>	<th>CORRESPONDING DELIVERABLE</th></tr>
<tr><td>Implement the Medallion Architecture in Databricks	</td><td>Bronze Layer Delta Table, Silver Layer Transformation, Gold Layer Views</td></tr>
<tr><td>Understand and manage data flow across layers	</td><td>Structured pipeline from Bronze → Silver → Gold</td></tr>
<tr><td>Enable data visualization and insights	</td><td>Databricks Dashboard built on Gold layer views</td></tr>
<tr><td>Ensure automation and scalability of the workflow	</td><td>Databricks Job Pipeline for end-to-end automation</td></tr>
</table>

