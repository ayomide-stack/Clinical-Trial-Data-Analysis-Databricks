# Clinical Trial Data Analysis — Databricks

**Exploratory and statistical analysis of clinical trial data using PySpark on Databricks.**

## Overview

This project performs data analysis on a clinical trial dataset using Databricks, applying PySpark for data ingestion, cleaning, and exploratory analysis. The notebook demonstrates working with structured health data at scale, applying summary statistics, and surfacing patterns relevant to trial outcomes.

## Tools & Stack

| Category | Stack |
|---|---|
| Language | Python (PySpark) |
| Platform | Databricks Community Edition |
| Data Processing | PySpark DataFrames, Spark SQL |
| Visualisation | Databricks built-in display, Matplotlib |

## Project Structure

```
clinical-trial-analysis-databricks/
├── TASK_1_CLINICAL_ANALYSIS_TRIAL.html    # Exported Databricks notebook
├── README.md
```

> Developed on Databricks Community Edition. The notebook is exported as HTML for portfolio viewing. To run interactively, import into a Databricks workspace.

## Methodology

- Loaded and ingested clinical trial dataset into PySpark DataFrame
- Applied data cleaning and type casting for analysis readiness
- Performed exploratory data analysis: distributions, summary statistics, missing value profiling
- Applied Spark SQL queries to filter and aggregate trial data
- Visualised key patterns in trial outcomes and patient demographics

## How to Run

1. Import the `.html` notebook into Databricks (File → Import → HTML)
2. Attach to an available Spark cluster
3. Upload clinical dataset to DBFS and update file path in the notebook
4. Run all cells sequentially

---

*MSc Data Science — Big Data & Cloud Computing module | University of Salford*
