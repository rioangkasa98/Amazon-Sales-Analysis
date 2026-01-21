# Analyzing Amazon Sales Data: Insights and Trends Using MySQL

## 1. Project Overview

This project involves analyzing Amazon sales data to extract key insights, identify top-selling products, and evaluate the performance of various sales channels and regions. The dataset includes various details related to sales transactions, including order information, product details, and shipping information.

## 2. Background

E-commerce has seen massive growth in recent years, with companies like Amazon leading the way. Understanding sales trends and customer behavior can help businesses optimize their operations, improve customer experiences, and drive revenue growth.

## 3. Goal

The primary goal of this project is to analyze sales performance, identify trends, and provide actionable insights to optimize Amazon’s sales strategy. The project will involve database design, SQL queries, and data analysis to answer important business questions.

## 4. Dataset Overview

Columns and Descriptions:

<img width="401" height="481" alt="image" src="https://github.com/user-attachments/assets/b53308f0-0919-4176-8a66-7930e79677bb" />

## 5. Approach Used

- **Data Cleaning**:
  Before analyzing the data, several cleaning steps were performed, including handling missing values, converting date formats, and ensuring consistency in the data types (e.g., ensuring that the "Amount" field is numeric).

- **Exploratory Data Analysis (EDA)**:
  Exploratory data analysis is done to answer the listed questions and aims of this project.

## 6. Business Questions

- **Product**
  1. What is the total revenue by product line?
  2. Which product line has the highest sales volume?
  3. What product line has the largest VAT?
  4. Which product had the largest revenue in the dataset?

- **Sales**
  1. Which city has the largest sales revenue?
  2. Which branch sold more products than average?
  3. What is the average amount of sales per product line?

- **Customer**
  1. What is the most common customer type?
  2. Which customer type generates the most revenue?
  3. What is the gender distribution of customers?

## 7. Analysis/Findings

**Summary of Insights**:
- Total sales by region
- Performance of products by category
- Effectiveness of different promotions on sales volume
- Shipping method impact on delivery speed and customer satisfaction

## 8. SQL Queries and Techniques

**Examples of SQL Queries**:
  - Aggregation: SELECT category, SUM(amount) AS total_sales FROM orders GROUP BY category
  - JOIN: SELECT orders.order_id, products.product_name FROM orders JOIN products ON orders.product_id = products.product_id

## 9. Challenges and Learnings

**Challenges**:
- Handling missing or inconsistent data
- Normalizing the dataset to ensure it’s relational

**Skills Learned**:
- Advanced SQL queries
- Data cleaning and transformation techniques
- Database optimization

## 10. Conclusion

**Summary**:
This project allowed me to explore the use of SQL in database design and analysis, while answering key business questions. Moving forward, I would explore further analyses using more advanced visualization tools or machine learning models for predictive analysis.

## 11. Technologies Used

**Tools and Languages**:
SQL (MySQL)
