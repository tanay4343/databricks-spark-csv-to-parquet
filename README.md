# Databricks Spark CSV to Parquet Pipeline

## Overview

This project demonstrates a simple **data processing workflow using Apache Spark in Databricks**.
The notebook reads a **CSV dataset**, loads it into a **Spark DataFrame**, inspects the schema, and converts the dataset into **Parquet format** for efficient storage and faster analytics.

## Steps Performed

1. Created a **SparkSession** using PySpark.
2. Loaded the CSV dataset into a **Spark DataFrame**.
3. Enabled `header` and `inferSchema` to correctly parse column names and data types.
4. Displayed the **schema and sample records** from the dataset.
5. Converted the dataset from **CSV format to Parquet format**.
6. Stored the Parquet file in **Databricks Volume (DBFS)**.
7. Reloaded the Parquet dataset to **verify schema and data**.

## Technologies Used

* Apache Spark
* PySpark
* Databricks

## Folder Structure

```
databricks-spark-csv-to-parquet/
│
├── notebooks/
│   └── spark_csv_to_parquet.py
│
├── data/
│   └── Product_records.csv
│
└── README.md
```

## Output

* The original **CSV dataset is successfully loaded into a Spark DataFrame**.
* The schema of the dataset is automatically inferred.
* The dataset is **converted and saved in Parquet format** for better performance.
* The Parquet file is stored in:

```
/Volumes/trainning/task-1/tasks/Product_records_parquet/
```

* The Parquet file is then **reloaded into Spark to verify the schema and records**.

## Key Learning

* Working with **Spark DataFrames**
* Reading **CSV data using PySpark**
* Writing **Parquet files for optimized storage**
* Managing files in **Databricks Volumes (DBFS)**

---

This project demonstrates a **basic data engineering workflow using Spark in Databricks**.
