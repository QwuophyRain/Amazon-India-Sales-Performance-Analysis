# Amazon India Sales Performance Analysis

**Author:** Rainsford Kofi Senam  
**Location:** Accra, Ghana  

## 📖 Description
Hi! Welcome to my data analysis project focusing on Amazon India's sales transactions. Real-world data is rarely perfect, so I built this project to showcase how to programmatically process messy data, extract meaningful business insights, and present intuitive visual dashboards. The primary goal of this analysis is to help management understand overall business performance and plan a data-driven strategy for the upcoming quarter. 

## 🎯 Role & Objective
* **Simulated Role:** Junior Data Analyst, Amazon India - Sales & Operations Team.
* **Objective:** To clean, explore, analyze, and visualize Amazon sales transactions. The final goal is to answer 10 specific business questions and provide actionable business recommendations to improve sales and profitability.

## ⚙️ Key Features & Workflow
* **Data Acquisition:** Utilizes a secure, native Google Colab file upload to ingest the dataset directly from a local machine, avoiding the need for complex API keys.
* **Smart Data Engineering:** I designed a custom auto-detection engine to map unpredictable column names to a standard schema. The pipeline also safely parses dates, drops duplicates, and derives missing "Total Sales" and "Profit" calculations on the fly.
* **KPI Analysis:** Computes critical business metrics including Total Revenue, Total Profit, Average Sale Value, and Profit Margins.
* **Exploratory Data Analysis:** Groups and sorts data to find total sales by State, Category, and Sub-Category.
* **Granular Insights:** Identifies the top 5 customers by revenue, the top 10 products by quantity sold, and the most preferred payment modes.
* **Time-Series Analysis:** Calculates the monthly sales trend to quickly spot seasonal peaks and low-performing months.

## 📊 Visualizations & Dashboards
Numbers are great, but visuals tell the story instantly. This notebook generates a 4-in-1 executive summary dashboard containing:
* **Bar Chart:** Total Sales by State.
* **Pie Chart:** Sales Distribution by Category.
* **Line Chart:** Monthly Sales Trend.
* **Horizontal Bar Chart:** Top 10 Products by Total Sales.

## ❓ Business Questions Answered
The analysis successfully addresses 10 core requirements set by management:
1. What is the total sales, total profit, and average order value?
2. Which state generated the highest and the lowest sales?
3. Which category and sub-category contributed the highest revenue?
4. Which are the Top 10 products based on sales?
5. Who are the Top 5 customers contributing the highest revenue?
6. Which payment mode is most preferred by customers?
7. Which month recorded the highest sales and profit? Is there any noticeable sales trend?
8. Identify any categories or products with high sales but low profit.
9. Which state or city requires improvement in sales performance?
10. Provide three actionable business recommendations that Amazon's management can implement.

## 🛠️ Tech Stack
* **Language:** Python 3.10
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter Notebook
