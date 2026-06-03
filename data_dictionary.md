# Data Dictionary: Sales Performance Analytics

## Dataset Overview
- **Source:** [Insert Kaggle/Institute Link Here]
- **Original License:** [e.g., CC BY 4.0 / Public Domain]
- **Format:** SQL Queries & Aggregated CSVs

## Variable Definitions

| Column Name | Data Type | Description | Unit/Format | Example |
| :--- | :--- | :--- | :--- | :--- |
| `order_id` | Integer | Unique transaction identifier | N/A | `58942` |
| `revenue` | Numeric | Total monetary value of sale | USD | `150.50` |
| `order_date` | Date | Timestamp of customer purchase | YYYY-MM-DD | `2026-06-03` |

## Data Transformation Notes
- Raw data extracted from PostgreSQL database using scripts in `/raw_queries`.
- Aggregated metrics exported to `/clean_exports` for Tableau dashboard ingestion.
