# Home Sales Data Analysis with PySpark

## Project Overview

This project focuses on analyzing home sales data using Apache Spark with PySpark. The analysis aims to extract meaningful insights from the data by utilizing Spark's powerful data processing capabilities, enabling efficient handling of large datasets.

## Dataset

The dataset used in this project is `home_sales_revised.csv`, which includes various details about home sales, such as sale date, build date, price, number of bedrooms and bathrooms, living area square footage, and more.

## Key Features

- Data loading and preprocessing with PySpark.
- Creation of temporary views for SQL-like data querying.
- Analysis of data to derive insights such as average prices and view ratings.
- Utilization of caching for performance optimization.
- Data partitioning and storage in Parquet format.
- Comparative analysis of query performance with and without caching.

## Analysis Queries

The project includes queries to answer questions such as:
- Average price of four-bedroom houses sold each year.
- Average price of homes with specific attributes (e.g., three bedrooms, three bathrooms) for each year they were built.
- "View" rating for homes with prices above a certain threshold.
- Performance comparison of queries with cached vs. non-cached data.

## Setup and Execution

### Prerequisites
- Apache Spark
- PySpark
- Jupyter Notebook or similar environment for running `.ipynb` files.

## License

[MIT License](LICENSE.md)
