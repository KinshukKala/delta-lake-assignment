# Delta Lake Incremental Processing using Databricks

## Project Overview

This project demonstrates incremental data processing using Delta Lake and Apache Spark in Databricks.

The project covers the complete workflow from loading raw CSV data into a Delta table to performing incremental updates using the MERGE operation.

---

## Technologies Used

- Databricks
- Apache Spark (PySpark)
- Delta Lake
- Python

---

## Dataset

Shopping Dataset

Files included:

- Combined_dataset.csv – Original dataset
- incremental_dataset.csv – Incremental records used for MERGE

---

## Project Workflow

### 1. Data Loading

- Load CSV dataset
- Create Delta Table

### 2. Data Cleaning

- Handle missing values
- Remove duplicate records

### 3. Incremental Processing

- Create incremental dataset
- Simulate updates
- Simulate new product insertions

### 4. Delta MERGE

- Update existing records
- Insert new records

### 5. Validation

- Verify row counts
- Check duplicate Product IDs
- Display final Delta table

---

## Repository Structure

delta-lake-assignment/
│
├── data/
├── notebooks/
├── report/
└── README.md

---

## Results

- Loaded CSV into Delta Lake

- Cleaned dataset

- Simulated incremental data

- Performed Delta MERGE successfully

- Validated final dataset

---

## Report

The report contains screenshots demonstrating every stage of the workflow, including:

- Data Loading
- Data Cleaning
- Incremental Processing
- MERGE Operation
- Validation
- Final Output

---

## Author

Kinshuk Kala
