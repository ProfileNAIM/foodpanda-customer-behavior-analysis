# foodpanda-customer-behavior-analysis
Exploratory data analysis of Foodpanda customer behavior, order trends, delivery performance, ratings, and churn using Python.
# Foodpanda Customer Behavior Analysis

## Project Overview

This project analyzes a Foodpanda dataset to understand customer behavior, order patterns, restaurant performance, payment preferences, delivery status, ratings, and customer churn.

The main goal of this project is to perform exploratory data analysis and generate business insights that can help improve customer retention, delivery performance, and sales strategy.

## Dataset

The dataset was collected from Kaggle: Foodpanda Analysis Dataset 2025.

It contains 6,000 records and 20 columns, including customer information, order details, restaurant data, payment method, loyalty points, ratings, delivery status, and churn status.

## Business Questions

This analysis focuses on answering the following questions:

- Which cities generate the highest number of orders?
- Which restaurants and dishes perform best?
- What are the most common payment methods?
- What is the delivery performance across different cities and restaurants?
- How do ratings vary by restaurant and delivery status?
- What factors are associated with inactive or churned customers?
- How do loyalty points and order frequency relate to churn?

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

1. Data loading and initial inspection
2. Data cleaning and formatting
3. Missing value analysis
4. Exploratory data analysis
5. Customer churn analysis
6. Data visualization
7. Business insights and recommendations

## Dataset Columns

| Column | Description |
|---|---|
| customer_id | Unique customer ID |
| gender | Customer gender |
| age | Customer age segment |
| city | Customer city |
| signup_date | Customer signup date |
| order_id | Unique order ID |
| order_date | Date of order |
| restaurant_name | Restaurant name |
| dish_name | Ordered dish |
| category | Food category |
| quantity | Quantity ordered |
| price | Order price |
| payment_method | Payment method used |
| order_frequency | Customer order frequency |
| last_order_date | Customer's last order date |
| loyalty_points | Loyalty points earned |
| churned | Customer status |
| rating | Customer rating |
| rating_date | Rating date |
| delivery_status | Delivery status |

## Key Insights

- City-wise order distribution helps identify high-demand locations.
- Restaurant and dish analysis shows which food items drive more sales.
- Delivery status analysis helps identify delayed and cancelled order patterns.
- Churn analysis helps understand inactive customer behavior.
- Loyalty points and order frequency can be useful indicators for customer retention.

## Recommendations

- Focus retention campaigns on inactive customers with low order frequency.
- Improve delivery performance in cities or restaurants with high delay or cancellation rates.
- Promote top-performing dishes and restaurants through targeted campaigns.
- Use loyalty points more strategically to encourage repeat purchases.
- Monitor customer ratings regularly to identify service quality issues.

## How to Run This Project

1. Clone the repository:

```bash
git clone https://github.com/ProfileNAIM/foodpanda-customer-behavior-analysis.git
