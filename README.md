# Customer Sales Analysis with Python

## Project Overview

This project uses Python and pandas to combine customer, order, and product datasets to analyze sales performance, purchasing behavior, and revenue trends.

The goal is to transform separate datasets into useful business insights through data cleaning, merging, aggregation, and analysis.

## Tools & Technologies

- Python
- pandas
- Jupyter Notebook
- CSV data processing

## Data Preparation

The project combines three datasets:

- `customers.csv` — Customer information
- `orders.csv` — Order transactions
- `products.csv` — Product information

The datasets are joined using `customer_id` and `product_id` to create a consolidated dataset for analysis.

Additional processing includes:
- Converting order dates to datetime format
- Calculating revenue from price and quantity
- Extracting order months
- Standardizing column names
- Exporting the merged dataset to CSV

## Analysis Performed

**Sales Performance**
- Total revenue
- Average order value (AOV)
- Top five products by revenue
- Top five products by quantity sold

**Customer Analysis**
- Total unique customers
- Top five customers by spending

**Regional Analysis**
- Number of orders by region
- Revenue by region

**Product & Time-Based Analysis**
- Revenue and quantity by product category
- Monthly revenue
- Highest monthly revenue

## Project Files

- `customer_sales_analysis.ipynb` — Python notebook containing data preparation and analysis
- `customers.csv` — Customer dataset
- `orders.csv` — Order dataset
- `products.csv` — Product dataset

## Running the Project

1. Download or clone the repository.
2. Install Python, Jupyter Notebook, and pandas.
3. Place the required CSV files in the same directory as the notebook.
4. Open `customer_sales_analysis.ipynb`.
5. Run the notebook cells in order.

## Skills Demonstrated

- Data integration and relational joins
- Data cleaning and transformation
- Exploratory data analysis
- Revenue and customer analytics
- Data aggregation and summarization
- Business performance reporting
