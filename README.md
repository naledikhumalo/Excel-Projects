# Coffee Orders Data Cleaning and Visualization

## Overview
This project focuses on cleaning, analyzing, and visualizing a coffee orders dataset. The dataset includes **Orders**, **Customers**, and **Sales** tables, which are used to analyze trends, customer behavior, and sales performance. Advanced Excel functions like **XLOOKUP**, **MATCH**, **INDEX**, and conditional logic using **IF statements** were utilized to clean and combine the data. Visualizations were created to provide insights into key metrics such as total sales over time, sales by country, and top customers.

## Project Goals
The primary objectives are:
- **Data Cleaning**: Ensuring data consistency, handling missing values, and joining multiple tables.
- **Data Lookup**: Using advanced Excel functions to connect tables and ensure accurate data retrieval.
- **Data Visualization**: Presenting clear insights using interactive visualizations that drive actionable conclusions.

## Dataset Details
The dataset includes multiple tables:
- **Orders Table**: Contains details about individual coffee orders, including coffee types, sizes, and quantities.
- **Customers Table**: Information about customer demographics and loyalty program participation.
- **Sales Table**: Details on total sales, dates, and regions (countries or cities).

## Steps Involved:

### Data Cleaning:
- **Handling Null Values**: Replaced null values with blank strings to ensure consistency.
- **Table Joins**: Connected the **Orders**, **Customers**, and **Sales** tables using functions like **XLOOKUP**, **MATCH**, and **INDEX**.
- **Standardization**: Ensured data such as dates and customer IDs were standardized across all tables.

### Advanced Excel Functions:
- **XLOOKUP**: Used to fetch corresponding data from other tables (customer information linked to order data).
- **MATCH and INDEX**: Applied to dynamically reference specific rows and columns based on conditions.
- **IF Statements**: Conditional logic applied to flag important attributes, such as loyalty card status, coffee names and invalid data entries.

### Pivot Tables and Visualizations:
- **Total Sales Over Time**: A line chart visualizing the total sales over a defined period.
- **Sales by Country**: A bar chart that breaks down sales by region to analyze performance across different countries.
- **Top 5 Customers**: A bar chart highlighting the top customers based on their order value or frequency.
- **Slicers**: Interactive slicers for filtering data by **Month**, **Coffee Type**, **Size**, and **Loyalty Card**.




