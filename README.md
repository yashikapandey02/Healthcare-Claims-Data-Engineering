# Healthcare-Claims-Data-Engineering
This project implements an end-to-end data engineering solution in Microsoft Fabric to process and analyze healthcare insurance claims. Using a Medallion Architecture, the pipeline transforms raw, unstructured claim files into a refined dimensional model, enabling stakeholders to track financial performance, and claim denial patterns.

## Architecture

![Architecture](./docs/Healthcare_Claims_Architecture.png)
 ## Tech Stack

| Category | Technology Used |
|----------|-----------------|
| Cloud Platform | Microsoft Fabric |
| Storage | Lakehouse (Delta Tables) |
| Data Processing | PySpark (Spark SQL) |
| Data Transformation | Dataflows Gen2 |
| Architecture | Medallion (Bronze / Silver / Gold) |
| Data Modeling | Star Schema (Fact & Dimension Tables) |
| BI & Visualization | Power BI |
| Version Control | Git & GitHub |
