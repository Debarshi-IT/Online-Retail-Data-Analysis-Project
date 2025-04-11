# Online-Retail-Data-Analysis-Project

## Project Overview
This project involves analyzing the Online Retail Dataset, which contains transactional data from an online retail store spanning 2010–2011. The goal is to explore the dataset, clean missing data, and generate insights about sales, customers, and products.

## Dataset Description
The dataset, Online Retail.xlsx, includes the following columns:

1. InvoiceNo: Invoice number of the transaction.
2. StockCode: Unique product code.
3. Description: Description of the product.
4. Quantity: Quantity of the product in the transaction.
5. InvoiceDate: Date and time of the transaction.
6. UnitPrice: Price per unit of the product.
7. CustomerID: Unique identifier for each customer.
8. Country: Country where the transaction occurred.

Download the dataset from here if working locally.

## Project Features
### Data Cleaning:
1. Handling missing values for Description and CustomerID.
2. Exploring patterns in missing data.

### Exploratory Data Analysis (EDA):
1. Identify top-selling products.
2. Analyze sales by country.
3. Understand customer behavior.

### Visualization:
1. Bar charts for top-performing products and countries.
2. Distribution of transactions with missing CustomerID.

### Flexible Analysis:
1.Support for analyzing data with and without missing CustomerID.
## Requirements
Make sure you have the following Python libraries installed:

pandas
numpy
matplotlib
openpyxl (for reading .xlsx files)
You can install these dependencies with: !pip install pandas numpy matplotlib openpyxl
