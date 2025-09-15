📊 CitySales360 – Sales & Order Analytics Project

This project simulates a real-world sales and order environment. The goal is to analyze product performance, monthly sales trends, brand revenue, city-wise orders, delivery status, and payment methods using Python. It includes one main dataset and multiple visualizations to practice data analysis and visualization techniques.

Project Overview

CitySales360 answers key business questions:
Which sub-products generate the highest revenue
Monthly sales trends and seasonal patterns
Revenue performance by brand
Top cities contributing to sales
Analysis of delivery status (Delivered vs Not Updated)
Popular payment methods among customers
The project uses Python, Pandas, Numpy and Matplotlib to process and visualize data.

CitySales360/
│
├── CitySales360.ipynb       # Main notebook with analysis and charts
├── data/                    # CSV dataset folder
│   └── sales_data.csv
├── README.md                # Project documentation
└── images/                  # Optional: screenshots of charts

📊 Dataset Overview
sales_data.csv
Column Name	Description
Order_ID	Unique ID for each order
Sub_Product	Name of the sub-product
Brand	Brand associated with the product
City	City where the order was placed
Year	Year of the order
Month	Month of the order
Total_Sales	Total sales amount for the order
Delivery_Status	Status of delivery (Delivered / Not Updated)
Payment_Mode	Mode of payment used by the customer

🔍 Analysis Overview

Top Selling Products: Identify sub-products with sales over 10,00,000
Monthly Sales Trends: Analyze month-wise revenue patterns
Brand Revenue: Compare total revenue across brands
City Orders: Find top cities contributing to sales
Delivery Status: Track Delivered vs Not Updated orders
Payment Mode Analysis: Understand customer payment preferences

📈 Visualizations

Bar Charts: Sub-product sales, Brand revenue, Payment modes
Line Charts: Monthly sales trends
Pie & Donut Charts: Top cities, Delivery status, Payment modes
Waterfall Charts: Payment mode counts

💻 Tech Stack

Python – Data analysis and manipulation
Pandas – Grouping, aggregation, and data cleaning
Matplotlib – Data visualization (line, bar, pie, donut, waterfall)
Jupyter Notebook – Interactive analysis environment

📌 Outcome

CitySales360 provides a 360° view of business performance, helping to:
Identify high-revenue products and brands
Understand monthly trends for inventory and marketing planning
Target top-performing cities
Improve delivery tracking and operational efficiency
Analyze popular payment methods
