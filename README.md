E-commerce Data Analysis Project

Overview

  This repository contains an E-commerce data analysis project that utilizes Python, Pandas, and MySQL to import and process data from various CSV files related to an e-commerce platform. The goal is to set up a database, load customer, order, product, and payment data, and conduct insightful analyses using SQL queries and visualization tools.

  



Project Structure

The project imports data from the following CSV files:

  customers.csv: Contains customer information.
  
  orders.csv: Details of customer orders.
  
  geolocation.csv: Customer geolocation data.
  
  products.csv: Information about products available.
  
  order_items.csv: Items associated with each order.
  
  payments.csv: Payment details for orders.
  
  sellers.csv: Information about sellers.
  




Technologies Used



  Python: For data manipulation and analysis.
  
  Pandas: For handling and processing data.
  
  MySQL: For storing and querying data.
  
  Matplotlib/Seaborn: For data visualization (to be integrated as needed).
  

Getting Started

  To set up the project on your local machine:
  

Install Required Packages:
  Make sure you have the necessary Python packages installed. You can use pip to install them if you haven't already:
  

  pip install pandas mysql-connector-python matplotlib seaborn
  

Set Up MySQL Database:
  Ensure you have MySQL installed and a database named ecommerce created. Modify the connection parameters in the code as needed:
  

conn = mysql.connector.connect(
    host='localhost',
    user='root',
    password='Password',
    database='ecommerce'
)


Load Data into MySQL:

  Run the provided script to load the CSV files into the MySQL database. The script reads each CSV file, creates corresponding tables if they don't exist, and populates the tables with data.

Data Analysis:

  You can query the MySQL database directly or integrate further analysis and visualization using Python.

Usage

  After loading the data, you can run SQL queries to perform analyses such as:

Analyzing customer demographics.

Evaluating sales performance.

Investigating product trends.

