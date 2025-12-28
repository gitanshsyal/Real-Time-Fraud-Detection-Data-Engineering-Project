# Real-Time-Fraud-Detection-Data-Engineering-Project
Built an end-to-end real-time fraud detection pipeline using modern lakehouse architecture (Bronze–Silver–Gold). The system ingests streaming data, performs data quality enforcement, event-time processing, deduplication, and fraud rule evaluation, and finally produces analytics-ready gold aggregates.
# Tech Stack:
Azure Data Lake Gen2 | Databricks | PySpark | Delta Lake | Structured Streaming | Auto Loader
# Architecture & Data Flow

Source → ADLS Gen2 (Landing) → Bronze → Silver → Gold

Datasets Ingested

Transactions

Customers

Card Details

Country Risk Scores

# Key Learnings & Highlights

Real-time ingestion using Auto Loader

Event-time based processing & watermarking

Delta Lake MERGE patterns with streaming

Stateful fraud detection with window aggregations

Production-ready Lakehouse architecture
