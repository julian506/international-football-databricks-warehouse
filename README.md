
# International Football Databricks Warehouse

This project takes the three CSV files from the [International football results from 1872 to 2024](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017/) dataset about the matches, the goalscorers and the shootouts of the international football results and creates dataframes using a Data Warehouse with a Snowflake structure in order to be able to analyze the data.

The project was built during my internship at Globant.

## Features

- Transformation of the CSV files into dataframes with a Data Warehouse with an Snowflake design
![International football (1)](https://github.com/julian506/international-football-databricks-warehouse/assets/56203236/bfd667ee-37d3-459c-8193-9976f5c54f8f)
- Creation of the Data Warehouse tables in the Hive Metastore.

## Requirements

1. You must have acces to a Databricks cluster in order to run this project.
2. You must upload the CSV files from the [International football results from 1872 to 2024](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017/) dataset (`goalscorers.csv`, `results.csv` and `shootouts.csv`) to the Hive Metastore of Databricks in order to be able to retrieve the data.
