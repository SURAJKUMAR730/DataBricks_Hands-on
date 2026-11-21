# Databricks Hands-on | Data Engineering Practice

This repository contains my hands-on practice and implementations of Data Engineering concepts using **Python, PySpark, Apache Spark and Delta Lake**.

The objective is to understand data manipulation, table operations and Slowly Changing Dimensions (SCD) used in data warehousing.

## Technologies Used

- Python
- PySpark
- Apache Spark
- Delta Lake
- Databricks Notebooks
- SQL

## Repository Contents

### 1. Data Manipulation

**File:** `Data manipulation (2).ipynb`

Notebook for practising data manipulation and working with data using PySpark.

### 2. SCD Type 1 Implementation

**File:** `SCD 1_Operation.ipynb`

Demonstrates SCD Type 1 operations using PySpark and Delta Lake.

Key concepts covered:
- Creating source and target tables
- Loading sample data
- Adding metadata columns
- Generating row-level hash values
- Using Delta Lake `MERGE` operations
- Updating existing records and inserting new records

### 3. SCD Type 2 Implementation

**File:** `SCD_02_Operation.ipynb`

Notebook dedicated to practising SCD Type 2 operations.

### 4. SCD Implementation Using Python

**File:** `SCD_Operation.py`

Python implementation related to SCD operations.

## How to Run

1. Open the notebooks in an Azure Databricks workspace.
2. Attach the notebook to a compatible cluster.
3. Review the sample data and table configurations.
4. Execute the notebook cells sequentially.
5. Verify the output tables after execution.

## Learning Objectives

- Understand PySpark DataFrame operations.
- Practise working with Spark tables.
- Understand Delta Lake table operations.
- Implement SCD concepts.
- Work with data insertion and updates.
- Improve practical Data Engineering skills.

---

**Author:** Suraj Kumar

[GitHub Profile](https://github.com/SURAJKUMAR730)
