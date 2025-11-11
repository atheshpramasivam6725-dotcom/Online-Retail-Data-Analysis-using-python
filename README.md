# Online-Retail-Data-Analysis-using-python
Project Description: Online Retail Data Analysis using Python
This project focuses on performing end-to-end data analysis on an Online Retail dataset using Python libraries like pandas, NumPy, and matplotlib. The goal is to clean, process, and visualize the data to extract meaningful business insights about sales performance, customer behavior, and product demand.
The project begins by importing essential libraries and loading the dataset (online_retail.csv) using pandas. A quick overview is displayed to understand the dataset structure, data types, and missing values.
In the data cleaning phase, duplicate records are removed using drop_duplicates(), and missing customer IDs are eliminated with dropna(). These steps ensure data reliability and consistency for accurate analysis.
Next, new calculated columns are added:
Revenue = Quantity × UnitPrice
Profit = 30% of Revenue (assumed margin)
Profit Margin (%) = (Profit / Revenue) × 100
This helps in measuring the profitability of products and transactions.
The project then calculates important Key Performance Indicators (KPIs):
Total Sales (₹) – Sum of all revenues
Total Orders – Count of unique invoices
Average Order Value (AOV) – Average revenue per order
Top 10 Products by Revenue – Most profitable products
Sales by Region (Country) – Country-wise revenue distribution
The cleaned dataset is saved as online_retail_cleaned.csv for future reference.
Data Visualization
To provide better insights, three major charts are plotted using Matplotlib:
Top 10 Products by Revenue (Bar Chart)
Displays the products that generated the highest revenue. This helps identify which items contribute most to total sales, supporting decisions on inventory focus and promotions.

Revenue by Country (Bar Chart)
Shows the total sales distribution across different countries. It helps pinpoint high-performing markets and regions that need marketing improvement.

Monthly Revenue Trend (Line Chart)
Converts the invoice date into a time series and plots monthly sales trends. This visualization helps track seasonal patterns, peak months, and business growth over time.

Outcome

The project provides a clear understanding of sales trends, customer distribution, and top-performing products.
Key outcomes include:

Clean and structured data ready for analysis

Identification of top 10 high-revenue products

Insights into best-performing regions

Visualization of monthly sales growth pattern

Estimated profitability and average order values

Overall, this project demonstrates how Python can transform raw retail data into actionable business intelligence through data cleaning, calculation, and visualization techniques.
