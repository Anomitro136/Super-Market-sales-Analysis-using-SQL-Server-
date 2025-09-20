## 🧮 Supermarket Sales Analysis with SQL Server

This project showcases a structured analysis of supermarket sales data using SQL Server. It includes a series of SQL queries aimed at uncovering key business metrics such as total sales, profit, payment trends, and performance breakdowns by gender, city, branch, and time periods.

## 📊 Project Overview
The dataset contains transactional records from a supermarket, including fields like invoice ID, gender, city, branch, payment method, quantity, tax, total, and timestamps. The objective is to transform raw data into actionable insights using SQL queries.

## 🛠️ Technologies Used

- SQL Server

## 📌 Key Insights Extracted

- Aggregate Metrics:
- Total Sales
- Total Profit
- Total Quantity Sold
- Total Tax Percentage
- Payment Analysis:
- Transaction count by payment method
- Demographic & Geographic Breakdown:
- Sales by Gender
- Sales by City
- Sales by Branch
- Time-Based Trends:
- Sales by Year
- Sales by Month
- Sales by Quarter

## 📁 File Structure

SQL_SERVER_PROJECT/

├── SQL SERVER PROJECT .pdf   # Contains all SQL queries used for analysis

├── README.md                    # Project documentation


## 🚀 How to Use

- Open MYSQL Workbench.
- Connect to your database containing the supermarket sales data.
- Run the queries provided in the PDF to generate insights.
- Customize or extend queries to explore additional business questions.
 
## 🧪 Sample Query: Total Sales by Branch

SELECT Branch, SUM(Total) AS Total_Sales
FROM sales..supermarket
GROUP BY Branch;


## 🔍 What It Does

- Groups transactions by branch.
- Calculates total sales for each branch.
- Helps identify which branches are performing best in terms of revenue.
  
## 📬 Contact

For questions, feedback, or collaboration opportunities, feel free to reach out via GitHub or LinkedIn.



