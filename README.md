# Home Sales Analysis

This project analyzes home sales data using Apache Spark, including SQL queries, caching, and parquet processing.

Project Overview

We use the home_sales dataset to answer key business questions:

✅ Calculate average home prices based on features (bedrooms, bathrooms, floors)
✅ Calculate average home price by year built (date_built)
✅ Calculate average home price per view rating, filtering for prices ≥ $350,000
✅ Compare query runtimes on uncached, cached, and parquet data
✅ Save data in parquet format partitioned by date_built

Technologies Used

Apache Spark
Python
Parquet (data storage format)
