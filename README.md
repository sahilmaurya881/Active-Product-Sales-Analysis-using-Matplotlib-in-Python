# 📊 Active Product Sales Analysis using Matplotlib in Python

This project analyzes product sales data, focusing on identifying the busiest purchase hours and the most popular products. It uses Python with libraries like Pandas, Matplotlib, and Numpy for data preprocessing, analysis, and visualization.

## 📋 Project Overview

The analysis includes:

- **Time-based Analysis**: Extracts and analyzes the busiest hours for purchases.
- **Product Popularity Analysis**: Lists the most frequently purchased products.
- **Data Visualization**: Line plot to show the number of purchases by hour and a table with the busiest hours.

## 📂 Key Files

- `Order_details-masked.csv`: The dataset containing order details, including transaction date and product information.
- `Active_Product_Sales_Analysis_using_Matplotlib_in_Python.ipynb`: Jupyter Notebook containing the entire analysis and visualizations.

## 📚 Libraries Used

- **Pandas**: For data manipulation and preprocessing.
- **NumPy**: For numerical operations.
- **Matplotlib**: For data visualization.
- **Collections (Counter)**: For counting product occurrences.

## 📝 Steps in Analysis

### 1. Data Loading and Preprocessing
   - Load the dataset from `Order_details-masked.csv`.
   - Convert the 'Transaction Date' column to datetime format for time-based analysis.
   - Extract the hour of each transaction to analyze hourly trends.

### 2. Analyze Busiest Purchase Hours
   - Count the transactions per hour to find the busiest hours for purchases.
   - Display a table showing the busiest hours and the cumulative number of purchases.

### 3. Visualization of Purchases by Hour
   - Create a line plot to show the number of purchases for each hour, highlighting the busiest times.

### 4. Product Popularity Analysis
   - Split multiple products in the 'Product' column to get individual counts.
   - Use the Counter class to count occurrences of each product.
   - Display the top 10 most frequently purchased products.

## 📊 Visualizations

- **Line Plot**: Shows the distribution of purchases by hour throughout the day.
- **Product Frequency Table**: Lists the top 10 most popular products based on purchase count.

## 🎯 Project Outcomes

This project provides insights into customer behavior and product popularity, which can help businesses:

- Optimize stock and staffing for peak purchase times.
- Identify best-selling products for targeted promotions and inventory management.

## 🛠️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/sahilmaurya881/Active-Product-Sales-Analysis-using-Matplotlib-in-Python.git
