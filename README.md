### Project Overview: Global Superstore Dashboard

#### Introduction
The project involves creating an interactive and insightful dashboard for a fictional company, Global Superstore, using a dataset obtained from Kaggle.com. The primary goal is to transform raw data into meaningful business insights, allowing stakeholders to make informed, data-driven decisions.

#### Objectives
1. **Data Cleaning**: Ensure the dataset is clean and free from errors or inconsistencies.
2. **Data Transformation**: Structure the data to facilitate analysis and visualization.
3. **Data Visualization**: Present key business metrics and insights through an interactive dashboard.

#### Data Cleaning and Transformation using Power Query Editor

1. **Remove Columns**:
   - **Objective**: Remove unnecessary columns that do not contribute to the analysis.
   - **Implementation**: Columns such as 'Postal Code' and 'Country' were removed using Power Query Editor by selecting the columns and using the 'Remove Columns' option.

2. **Split Columns**:
   - **Objective**: Split columns that contain multiple pieces of information into separate columns for clarity.
   - **Implementation**: The 'Order Date' column was split into 'Order Year', 'Order Month', and 'Order Day' using the 'Split Column by Delimiter' feature in Power Query Editor.

3. **Replace Errors**:
   - **Objective**: Identify and correct errors within the dataset.
   - **Implementation**: Errors in 'Sales' and 'Profit' columns were identified and corrected using the 'Replace Errors' functionality in Power Query Editor.

4. **Replace Null Values**:
   - **Objective**: Handle missing values to ensure data integrity.
   - **Implementation**: Null values in columns like 'Customer ID' and 'Product ID' were replaced using the 'Replace Values' or 'Fill Down' options in Power Query Editor.

5. **Merge Columns**:
   - **Objective**: Combine multiple columns to create a single, more informative column.
   - **Implementation**: 'City' and 'State' columns were merged into a 'Location' column using the 'Merge Columns' feature in Power Query Editor.

6. **Extract Necessary Data**:
   - **Objective**: Filter out unnecessary data, focusing only on relevant information.
   - **Implementation**: Data was filtered to include only transactions from the past five years using the 'Filter Rows' functionality in Power Query Editor.

#### Data Analysis and Visualization using Power BI

The clean and transformed data was then used to create a comprehensive dashboard in Power BI with the following features:

1. **Sales Analysis**:
   - **Total Sales**: Visual representation of total sales over time using line charts and bar charts.
   - **Sales by Category**: Breakdown of sales by product categories and sub-categories using pie charts and stacked bar charts.

2. **Profit Analysis**:
   - **Profit Trends**: Monthly and yearly profit trends to identify peak periods using line charts.
   - **Profit by Region**: Geographic analysis of profit distribution using maps and filled maps.

3. **Customer Insights**:
   - **Top Customers**: Identification of top-performing customers in terms of sales and profit using bar charts and tables.

4. **Operational Metrics**:
   - **Order Processing Time**: Analysis of order processing times to identify bottlenecks using line charts and histograms.
   - **Shipping Performance**: Evaluation of shipping times and performance by region using bar charts and maps.

#### Tools and Technologies

- **Data Cleaning and Transformation**: Power Query Editor
- **Data Visualization**: Power BI for creating interactive dashboards
- **Data Source**: Global Superstore dataset from Kaggle

#### Conclusion

The creation of the Global Superstore Dashboard involved meticulous data cleaning and transformation processes using Power Query Editor to ensure data accuracy and reliability. The final dashboard, developed in Power BI, provides an interactive and comprehensive view of the company's performance, allowing stakeholders to make informed decisions based on real-time data insights. This project showcases the importance of data preprocessing and the power of data visualization in driving business success.
