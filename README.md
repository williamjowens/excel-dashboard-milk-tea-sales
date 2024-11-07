# Excel Dashboard - Milk Tea Sales

This project is an Excel-based dashboard and reporting tool for milk tea sales data. It provides insights into customer preferences, monthly sales by flavor and size, top customers, and country-based sales distribution. The project includes raw and processed data, pivot tables, and a dashboard for easy analysis and visualization.

## Project Structure

The project is organized as follows:

- **dashboard/**: Contains the main Excel dashboard file and screenshots.
  - `Dashboard.xlsx`: The main dashboard file with interactive visuals for data exploration.
  - `dashboard_screenshot.png`: A screenshot of the dashboard for reference.

- **data/**: Contains raw and final data files along with example screenshots and function usage.
  - **final/**: Finalized data files and function usage screenshots.
    - `customers_table_sample_screenshot.png`: Sample screenshot of the customers table.
    - `final_milk_tea_sales_data.xlsx`: Finalized milk tea sales data in Excel format.
    - `function_usage_if_xlookup.png`: Example of IF and XLOOKUP function usage.
    - `function_usage_index_match.png`: Example of INDEX and MATCH function usage.
    - `function_usage_xlookup.png`: Example of XLOOKUP function usage.
    - `orders_table_sample_screenshot.png`: Sample screenshot of the orders table.
    - `products_table_sample_screenshot.png`: Sample screenshot of the products table.
  - **raw/**: Original raw data files and data preparation script.
    - `customers_complete.csv`: Complete list of customers.
    - `merged_workbook.xlsx`: Merged workbook containing all raw data.
    - `orders_complete.csv`: Complete list of orders.
    - `products_complete.csv`: Complete list of products.
    - `milk_tea_data_creation_and_validation.ipynb`: Jupyter notebook for data creation and validation.

- **pivot_tables/**: Contains pivot tables for different analyses and screenshots.
  - `monthly_sales_by_flavor.xlsx`: Pivot table showing monthly sales by flavor.
  - `monthly_sales_by_flavor_screenshot.png`: Screenshot of the monthly sales by flavor pivot table.
  - `monthly_sales_by_size.xlsx`: Pivot table showing monthly sales by size.
  - `monthly_sales_by_size_screenshot.png`: Screenshot of the monthly sales by size pivot table.
  - `top_5_customers.xlsx`: Pivot table of the top 5 customers by sales.
  - `top_5_customers_screenshot.png`: Screenshot of the top 5 customers pivot table.
  - `total_sales_by_country.xlsx`: Pivot table showing total sales by country.
  - `total_sales_by_country_screenshot.png`: Screenshot of the total sales by country pivot table.

- **milk_tea_sales_full_workbook.xlsx**: The comprehensive Excel workbook containing all data, pivot tables, and the dashboard.