# Data-Engineering-Project-with-Databricks
This project implements a complete end-to-end data engineering pipeline on Databricks Free Edition, designed to mimic a real-world Fast-Moving Consumer Goods (FMCG) industry use case. Using a structured Lakehouse architecture with Delta Lake and Spark, the pipeline ingests, processes, and consolidates multi-source retail data to produce trusted analytical datasets that support business reporting and decision-making.

# Problem Statement
A fast-growing sports equipment manufacturing company has a mature and well-structured ETL pipeline, centralized storage, and clean, consolidated reporting data.
This company recently acquired a smaller company that produces sport bars. Unlike the parent company’s organized data ecosystem, the newly acquired company’s data was scattered across multiple unstructured sources — spreadsheets, cloud drives, email attachments, and even WhatsApp exports.

This created an immediate challenge:
How can we integrate two companies with completely different data maturity levels?
How can the scattered, inconsistent, unclean data from the small company be transformed to match the parent comapny’s enterprise-level data model?
How can both datasets be merged into one unified source of truth without disrupting existing analytics and reporting?

To address this, I implemented an end-to-end data engineering solution using Databricks. The goal was to ingest the acquired company’s unstructured data, standardize its format, enforce data quality, and merge it with parent company’s existing data model — enabling reporting, analytics, and business decisions across the newly combined organization.

# Tech Stack Used
| Layer                   | Tools & Technologies                |
| ----------------------- | ----------------------------------- |
| Compute & Orchestration | Databricks Notebooks, Jobs          |
| Processing              | Apache Spark (PySpark / SQL)        |
| Storage                 | Delta Lake (Medallion architecture) |
| Data Source             | AWS S3 Bucket                       |
| Visualization           | Dashboard                           |
| Version Control         | GitHub                              |


# Architecture

<img width="1920" height="1080" alt="Workflow Diagram Planning Whiteboard in Green Yellow Modern Professional Style" src="https://github.com/user-attachments/assets/9f4b14b7-0d9f-42fb-871e-941dfb45c5b1" />



