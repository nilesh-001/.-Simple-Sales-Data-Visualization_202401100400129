# Sales Data Visualization Project

## Overview
This project focuses on analyzing and visualizing sales data to understand revenue trends, product demand, and seasonal variations. The dataset is generated synthetically and includes daily sales records for multiple products over a year.

## Problem Statement
The goal is to analyze and visualize revenue, product demand, and seasonal sales trends. By doing so, we aim to identify key insights into sales performance and how different factors influence revenue generation.

## Dataset
The dataset consists of:
- **Date:** The transaction date.
- **Product:** Name of the product sold.
- **Category:** Product category (e.g., Electronics, Accessories, Wearables).
- **Units Sold:** The number of units sold per day.
- **Revenue:** The total revenue generated for that product on a given day.

### Special Adjustments:
- Seasonal sales trends are accounted for by increasing revenue by 50% during November and December.
- Randomized demand and pricing ensure variability across the dataset.

## Implementation Steps
1. **Data Generation:** A dataset with daily sales records for five product types was created using Python.
2. **Data Processing:** The dataset was structured into a Pandas DataFrame for easy manipulation.
3. **Visualization:** The following visualizations were generated:
   - **Daily Revenue Trend:** A time-series plot showing revenue fluctuations.
   - **Product Demand:** A bar chart comparing units sold across different products.
   - **Seasonal Trends:** A line chart displaying revenue patterns across different months.

## Results
The visualizations provide insights into:
- How revenue changes over time.
- Which products have higher demand.
- The impact of seasonal trends on sales.

## Conclusion
This project demonstrates how sales data can be analyzed to uncover trends and patterns. The generated dataset and visualizations help in making data-driven decisions for better sales strategies.

## Files Included
- `sales_data.csv`: The generated dataset.
- `sales_analysis.ipynb`: The Jupyter Notebook with code and visualizations.
- `README.md`: This file explaining the project.

## Credits
This dataset was synthetically generated, and the visualizations were created using Python libraries such as Pandas, Matplotlib, and Seaborn.

