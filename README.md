# Sales-Dashboard-Using-Power-BI-Excel

## Overview

This project showcases a complete *end-to-end data analysis and visualization* pipeline using *Power BI and Excel. It focuses on building a dynamic **Sales Dashboard* that helps track key performance indicators (KPIs) such as *Revenue, Quantity Sold, and Customer Insights* across regions, products, and time.

## Tools Used
- *Microsoft Excel* – Data cleaning and preprocessing
- *Power BI* – Data visualization and dashboard creation
- *GitHub* – Version control and project documentation

## Data Description

The dataset contains 500 rows of *dummy sales data* with the following columns:
- Order Date
- Customer Name
- Product
- Region
- Unit Price
- Revenue
- Quantity Sold (calculated)
- Category

Some columns contained:
- *Missing values* (in Customer Name and Region)
- *Inconsistent formatting and extra spaces*
- *Unordered columns (later rearranged from A–H)*

## Data Cleaning Steps (in Excel)

- Swapped columns A–H for better readability
- Trimmed extra spaces using =TRIM() function
- Calculated *Quantity Sold* using: =Revenue / Unit Price
- Highlighted and analyzed missing values
- Filled missing *Region* as "Unknown"
- Removed rows with missing *Customer Name*
- Ensured numeric columns were correctly typed

## Power BI Dashboard

### Visualizations Included:
1. *Total Sales Overview (Revenue)*
2. *Sales Over Time (Year-wise)*
3. *Top 10 Customers by Revenue*
4. *Top 5 Products by Revenue*
5. *Sales by Region*
6. *Revenue vs Quantity Sold (Scatter Plot)*
7. *Category-wise Sales Distribution*
8. *Missing Region Count (Card Visual)*

## Features:
- Clean, minimal layout using borders and sections
- Text headers for visual separation
- Interactive filtering and dynamic visuals

## Key Insights

- Certain *products and customers* contribute significantly to revenue.
- Positive correlation between *quantity sold and revenue*.
- Some *regions had missing data*, labeled as "Unknown" for tracking.
- Top 10 customers drive a large share of overall sales.
- Product categories show uneven revenue contributions.Built interactive reports tracking KPIs across regions and products.
