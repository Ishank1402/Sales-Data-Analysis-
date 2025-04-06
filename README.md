# Sales-Data-Analysis

# 📌  Project Description

This project analyzes sales data using Python to uncover insights related to product sales, revenue generation, and customer purchase behavior. 
The dataset includes sales transactions with details like product name, quantity ordered, price, and order date. Visualizations are used to present key trends in the data.


## Dataset Used: https://www.kaggle.com/datasets/beekiran/sales-data-analysis/data


# 📊 Key Metrics / Indicators (KPIs)

1. Revenue Calculation: Derived by multiplying "Quantity Ordered" and "Price Each".
2. Top-Selling Products: Ranked products by quantity sold.
3. Sales Over Time: Temporal analysis using order dates to explore time-based trends.
4. Data Cleaning: Handled missing values and converted data types for analysis.
5. Revenue Contribution: Identified which products or categories contribute most to total revenue.


# ⚙️ Process:

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
     
# Visuals

![1](https://github.com/user-attachments/assets/07bab319-6aa0-43b5-84b2-d396e1bf16ac)


![2](https://github.com/user-attachments/assets/4f570979-f893-439c-8e3a-175993330230)


![3](https://github.com/user-attachments/assets/1878d77b-8abf-482c-8efd-9750c38b7fa1)


![4](https://github.com/user-attachments/assets/3dbbbbe1-31b1-4433-82d0-c7de6a5245f7)


![5](https://github.com/user-attachments/assets/27921646-88aa-4629-bf8d-ba82438f695b)


![6](https://github.com/user-attachments/assets/1ce96760-6156-4309-9089-23b5107dbd7b)


![7](https://github.com/user-attachments/assets/aa52c3df-75eb-430a-a727-22d74d95e52b)


# 🧠 Conclusion:

From the sales data analysis and the chart showing the Top 10 Most Sold Products, we can conclude the following:

Popular Demand: The most frequently purchased products are those that likely meet everyday needs or are competitively priced. These products had significantly higher order volumes than others.

Product Trends: Some products clearly stand out in terms of quantity sold, suggesting they are customer favorites and should be prioritized for stock and promotion.

Sales Strategy Insight: The chart highlights which products drive volume-based sales — useful for bulk discounting strategies or upselling bundles.

Business Focus Areas: Focusing marketing or supply chain efforts on the top 10 products could improve overall efficiency and profitability since these are the key revenue drivers by quantity.
