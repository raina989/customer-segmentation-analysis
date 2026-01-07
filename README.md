# Customer Segmentation Analysis 🧩

## Project Overview
This project focuses on customer segmentation using sales transaction data. The objective is to group customers based on their purchasing behavior in order to help businesses understand different customer types and tailor marketing strategies accordingly.

## Objectives
- Aggregate customer-level purchase data
- Identify distinct customer segments using clustering
- Analyze purchasing patterns across different customer groups
- Provide actionable business insights based on customer behavior

## Dataset
Sample Superstore Dataset (Kaggle)

## Features Used for Segmentation
- Total Sales per Customer
- Total Quantity Purchased
- Average Discount per Customer

## Methodology
- Data aggregation using Pandas
- Exploratory analysis of customer behavior
- Customer segmentation using K-Means clustering
- Visualization of customer segments

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Key Insights
- Customers can be broadly divided into three segments: high-value, medium-value, and low-value customers.
- High-value customers generate the majority of total sales and purchase larger quantities with lower average discounts.
- Medium-value customers show consistent purchasing behavior with moderate sales and quantity.
- Low-value customers contribute smaller sales amounts and often rely on higher discounts.

## Visualizations
- `customer_segments.png` – Scatter plot showing customer clusters based on sales and quantity.
- `discount_distribution.png` – Histogram showing the distribution of discount values across orders. The visualization indicates that most orders receive low or no discounts, while higher discount levels are used less frequently. This suggests that discounts are applied selectively, likely to stimulate demand or clear inventory.
- `sales_distribution.png` – Histogram showing the distribution of sales values across orders. The distribution is right-skewed, indicating that most orders have low sales amounts, while a small number of orders contribute to very high sales values. This suggests that a few large transactions drive overall revenue.

## Business Recommendations
- Focus retention and loyalty programs on high-value customers.
- Use targeted promotions to convert medium-value customers into high-value ones.
- Apply controlled discount strategies for low-value customers to improve profitability.

## Future Improvements
- Include customer lifetime value (CLV) analysis
- Test different numbers of clusters
- Deploy an interactive dashboard using Streamlit

## Author
Raina Khanam
