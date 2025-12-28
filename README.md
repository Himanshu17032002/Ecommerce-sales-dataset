🛒 E-Commerce Sales Data Analysis

Using MySQL & Python

📌 Project Overview

This project focuses on analyzing an E-commerce sales dataset using MySQL for data storage and querying and Python for data analysis and visualization.
The goal is to extract meaningful business insights such as sales trends, customer behavior, product performance, and revenue growth.


🧰 Tech Stack

Database: MySQL

Programming Language: Python

Libraries Used:

pandas

numpy

matplotlib

seaborn

mysql-connector-python / sqlalchemy

Tools: Jupyter Notebook, MySQL Workbench

📂 Dataset Description

The dataset represents transactional data from an E-commerce platform.

Main Tables Used

customers → customer_id, customer_unique_id, customer_zip_code, customer_city, customer_state

geolocation → geolocation_zip_code_prefix, geolocation_lat, geolocation_lng, geolocation_city, geolocation_state

order_items → order_id, order_item_id, product_id, seller_id, shipping_limit_date, price, freight_value

orders → order_id, customer_id, order_status, order_purchase_timestamp, order_approved_at, order_delivered_carrier_date, order_delivered_customer_date, order_estimated_delivery_date

payments → order_id, payment_sequential, payment_type, payment_installments, payment_value

products → product_id, product category, product_name_length, product_description_length, product_photos_qty, product_weight_g, product_length_cm, product_height_cm, product_width_cm

seller → seller_id, seller_zip_code_prefix, seller_city, seller_state


⚙️ Project Workflow

Data Import

   Imported raw CSV data into MySQL tables.

   Created schema and applied constraints.

Data Cleaning (SQL & Python)

   Removed null values and duplicates.

   Standardized date formats.

   Validated numerical fields.

SQL Analysis

   Revenue by month and year

   Top-selling products

   Category-wise sales

   Customer purchase frequency

   High-value customers

Python Analysis

   Connected MySQL database using Python

   Data extraction using SQL queries

   Performed exploratory data analysis (EDA)

   Visualized insights using charts

   
🚀 How to Run the Project

Clone the repository

Import dataset into MySQL

Update database credentials in Python script

Run Jupyter Notebook / Python script

Explore insights and visualizations

🎯 Learning Outcomes

Hands-on experience with MySQL queries

Real-world data analysis using Python

Understanding of E-commerce business metrics

Data visualization and insight generation

📌 Future Enhancements

Add dashboard using Power BI / Tableau

Implement predictive sales forecasting

Automate ETL pipeline

Deploy analysis using Streamlit

👤 Author

Himanshu Prasad

Skills: MySQL, Python, Data Analysis, SQL, Visualization

Aspiring Data Analyst
