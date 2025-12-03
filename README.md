# Databricks ETL Pipeline (Bronze → Silver → Gold)
This project demonstrates an end-to-end ETL pipeline built on Azure Databricks using the medallion architecture.
It includes data ingestion, transformation, incremental loading, and Delta Lake optimisation.

**Architecture**

Bronze Layer: Raw data ingestion

Silver Layer: Cleaned, deduplicated, and validated data

Gold Layer: Business-ready aggregated tables for analytics

**Technologies Used**

Azure Databricks

PySpark

Delta Lake

GitHub (version control)

Medallion Architecture (Bronze/Silver/Gold)

**Key Features**

Automated data ingestion using Autoloader

Full + incremental load pipeline

Surrogate key generation

Delta Lake optimisations (Z-Ordering, vacuum, compaction)

Parameterised pipeline logic

Modular notebook workflow

**Repository Structure**

/notebooks

    ├── bronze_ingestion.py
    ├── silver_transformation.py
    ├── gold_aggregation.py
