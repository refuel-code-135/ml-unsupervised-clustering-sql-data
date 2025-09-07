# sql-customer-analytics-ecommerce

## Project Overview

This project analyzes the Northwind database, a classic retail dataset containing orders, products, categories, and customer information.  
The goal is to uncover sales patterns and customer/product segments through:  

- Exploratory Data Analysis (EDA) of 14 relational tables
- Identifying top-performing products and seasonal trends
- Applying KMeans clustering to detect potential customer/product segments

By combining SQL queries, traditional analysis, and machine learning, this notebook demonstrates a practical workflow for extracting business insights from relational data.  

## Notebook

https://github.com/refuel-code-135/ml-unsupervised-clustering-sql-data/blob/main/notebooks/notebook.ipynb

## data

This project uses the Northwind database (licensed under the MIT License).

https://github.com/jpwhite3/northwind-SQLite3/tree/main

Copyright (c) 2016 JP White


## Set Up Analysis environment

```bash
export CONDA_ENV=ml-unsupervised-clustering-sql-data

# Create and activate a new conda environment
conda create -n $CONDA_ENV python=3.12
conda activate $CONDA_ENV

# Install required Python packages
pip install -r requirements.txt

# Start notebook
jupyter lab
```

