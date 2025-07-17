📊 Amazon Sales Data Analysis
📌 Dataset Overview

This project analyzes Amazon sales transactions to uncover insights into purchasing behavior, revenue trends, and customer demographics. 
The dataset contains 250 records of sales transactions, including product details, customer information, payment methods, and order statuses.

🔗 Dataset Source: https://www.kaggle.com/datasets/zahidmughal2343/amazon-sales-2025 

📂 Dataset Description
Columns & Features
Column Name	Description	Example Values
Order ID	Unique identifier for each order.	ORD0001, ORD0002
Date	Date of the order.	2023-05-15, 2023-06-22
Product	Name of the product purchased.	Wireless Earbuds, T-Shirt
Category	Product category.	Electronics, Clothing, Home Appliances
Price	Price of a single unit (in USD).	49.99, 19.99
Quantity	Number of units purchased in the order.	1, 3
Total Sales	Total revenue from the order (Price × Quantity).	49.99, 59.97
Customer Name	Name of the customer (anonymized if necessary).	Customer_A, Customer_B
Customer Location	City where the customer is based.	New York, Los Angeles
Payment Method	Mode of payment used.	Credit Card, Debit Card, PayPal
Status	Order status (Completed, Pending, Cancelled).	Completed, Pending

🎯 Project Objectives

This analysis aims to:
✔ Explore sales trends by category, time, and location.
✔ Identify top-selling products and customer preferences.
✔ Analyze payment method popularity across regions.
✔ Predict Total Sales using ML models.
✔ Visualize revenue patterns with matplotlib/seaborn.

🛠️ Tools & Techniques Used

    Data Cleaning: Handling missing values, outliers.

    Exploratory Data Analysis (EDA): Statistical summaries, correlation analysis.

    Visualization: seaborn, matplotlib

    Key Libraries: pandas, numpy, scikit-learn, XGBoost, LightGBM.

