# Amazon India Sales Performance Analysis[cite: 1]

## 📖 Description
This repository contains a data analysis project focused on Amazon India's sales transaction data[cite: 3]. The management team requires an understanding of overall business performance to plan the strategy for the upcoming quarter[cite: 3]. This project serves to clean the data, extract insights, and present visual dashboards to guide data-driven decisions[cite: 3]. 

## 🎯 Role & Objective
*   **Role:** Junior Data Analyst, Amazon India - Sales & Operations Team[cite: 1].
*   **Objective:** To clean, explore, analyze, and visualize Amazon sales transactions[cite: 1]. The final goal is to answer 10 specific business questions and provide actionable business recommendations to improve sales and profitability[cite: 1, 3].

## ⚙️ Key Features & Workflow
*   **Data Acquisition:** Features an auto-download implementation using the Kaggle API to fetch the dataset directly[cite: 1].
*   **Data Cleaning:** Includes auto-detection mapping for column names, parsing date columns, dropping duplicate rows, filling null values, and deriving missing "Total Sales" and "Profit" calculations[cite: 1].
*   **KPI Analysis:** Computes critical business metrics including Total Sales, Total Profit, Profit Margin (%), Total Orders, Average Sale Value, Maximum Sales, and Minimum Sales[cite: 1, 3].
*   **Exploratory Data Analysis:** Groups and sorts data to find total sales by State, Category, and Sub-Category[cite: 1, 3].
*   **Granular Insights:** Identifies the top 5 customers by revenue, the top 10 products by quantity sold, and the most preferred payment modes[cite: 1, 3].
*   **Time-Series Analysis:** Calculates the monthly sales trend to find peak and low sales months[cite: 1, 3].

## 📊 Visualizations & Dashboards
The notebook generates a 4-in-1 summary presentation dashboard containing the following charts[cite: 1]:
*   **Bar Chart:** Total Sales by State[cite: 1, 3].
*   **Pie Chart:** Sales Distribution by Category[cite: 1, 3].
*   **Line Chart:** Monthly Sales Trend[cite: 1, 3].
*   **Horizontal Bar Chart:** Top 10 Products by Total Sales[cite: 1, 3].

## ❓ Business Questions Answered
The analysis successfully addresses the following requirements set by management[cite: 3]:
1. What is the total sales, total profit, and average order value?[cite: 3]
2. Which state generated the highest and the lowest sales?[cite: 3]
3. Which category and sub-category contributed the highest revenue?[cite: 3]
4. Which are the Top 10 products based on sales?[cite: 3]
5. Who are the Top 5 customers contributing the highest revenue?[cite: 3]
6. Which payment mode is most preferred by customers?[cite: 3]
7. Which month recorded the highest sales and profit? Is there any noticeable sales trend?[cite: 3]
8. Identify any categories or products with high sales but low profit.[cite: 3]
9. Which state or city requires improvement in sales performance?[cite: 3]
10. Provide three actionable business recommendations that Amazon's management can implement.[cite: 3]

## 🛠️ Tech Stack
*   **Language:** Python 3.10.0[cite: 1]
*   **Data Manipulation:** Pandas, NumPy[cite: 1]
*   **Data Visualization:** Matplotlib, Seaborn[cite: 1]
*   **Environment:** Jupyter Notebook / Google Colab[cite: 1]
