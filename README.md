# Sales-Data-Analysis-

# Project Description

This project analyzes sales data using Python to uncover insights related to product sales, revenue generation, and customer purchase behavior. 
The dataset includes sales transactions with details like product name, quantity ordered, price, and order date. Visualizations are used to present key trends in the data.

## Dataset Used:
Sales dataset containing transaction-level data including order date, product, quantity, and price.

# Key Metrics / Indicators (KPIs)

1. Revenue Calculation: Derived by multiplying "Quantity Ordered" and "Price Each".
2. Top-Selling Products: Ranked products by quantity sold.
3. Sales Over Time: Temporal analysis using order dates to explore time-based trends.
4. Data Cleaning: Handled missing values and converted data types for analysis.
5. Revenue Contribution: Identified which products or categories contribute most to total revenue.
6. 
#Process:

1. Data Loading: Loaded the dataset into a Pandas DataFrame from a CSV file.
2. Data Cleaning:
   - Checked and handled missing or null values.
   - Standardized column types and converted 'Order Date' to datetime format.
3. Feature Engineering:
   - Created a new column "Revenue" by multiplying "Price Each" with "Quantity Ordered".
4. Data Aggregation:
   - Grouped and summarized data by product to identify top-selling items.
   - Analyzed overall revenue and sales trends.
5. Data Visualization:
   - Created bar charts using Matplotlib to visualize:
   - Top 10 most sold products.
   - Other trends and insights (e.g., monthly revenue or product-wise revenue if available).
6. Insight Generation:
   - Identified key patterns from the visualizations for business decision-making.
     
# Visuals:
https://github.com/Ishank1402/Sales-Data-Analysis-/blob/main/1.png

https://github.com/Ishank1402/Sales-Data-Analysis-/blob/main/2.png

https://github.com/Ishank1402/Sales-Data-Analysis-/blob/main/3.png

https://github.com/Ishank1402/Sales-Data-Analysis-/blob/main/4.png

https://github.com/Ishank1402/Sales-Data-Analysis-/blob/main/5.png

https://github.com/Ishank1402/Sales-Data-Analysis-/blob/main/6.png

https://github.com/Ishank1402/Sales-Data-Analysis-/blob/main/7.png

# Conclusion:

This Python-based sales analysis provides clear insights into which products are driving the highest revenue and sales volume. 
By examining order data, businesses can identify key performers, spot trends over time, and make informed inventory and marketing decisions. 
The approach demonstrates how Python can be effectively used for real-world business data analysis with minimal tooling.
