# Insurance Data Flow


Policy System
        |
Customer System
        |
Claims System
        |
Payment System

        ↓

Azure Data Factory

        ↓

ADLS Gen2

        ↓

Bronze Layer

        ↓

Databricks PySpark

        ↓

Silver Delta Tables

        ↓

Gold Data Warehouse Tables

        ↓

Power BI Dashboard
