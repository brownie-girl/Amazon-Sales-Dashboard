Amazon Sales Dashboard

An end-to-end data analytics project analyzing Amazon sales data — from raw data cleaning in Python to an interactive Power BI dashboard.

 Project Overview :-
This project takes raw Amazon sales transaction data through a full analytics pipeline: cleaning and preprocessing with Python (Pandas), followed by dashboard design and DAX-based analysis in Power BI. The goal was to surface key business insights — sales trends, order fulfillment performance, category-wise revenue, and top-performing products.

Tech Stack

Python (Pandas) — data cleaning and preprocessing
Power BI Desktop — data modeling, DAX measures, and dashboard visualization
DAX — custom measures for KPIs and aggregations


 Data Cleaning (Python)

The raw dataset was cleaned and prepared using Pandas, including steps such as:

Handling missing/null values
Standardizing date and category formats
Removing duplicate records
Validating numeric fields (UnitPrice, Quantity, Discount, TotalAmount)
Exporting a clean dataset ready for Power BI import

Dashboard Features
KPI Cards
Average Unit Price
Total Sales Amount
Total Discount
Total Quantity Sold


Visuals
Sales by Order Status — breakdown of Delivered, Shipped, Pending, Cancelled, and Returned orders
Sales Trend by Year (2020–2024) — line chart tracking revenue over time
Sales by Category — horizontal bar chart comparing revenue across product categories (Electronics, Sports & Outdoors, Books, Clothing, Toys & Games, Home & Kitchen)
Top 10 Products Table — ranks top-performing products by total sales amount using a Top N DAX filter


Interactivity
Year/Quarter/Month hierarchy slicer for dynamic time-based filtering
Cross-filtering across all visuals
 Repository Structure

├── data/
│   ├── raw/                # original unprocessed data
│   └── cleaned/             # output from Python cleaning step
├── scripts/
│   └── data_cleaning.py     # Pandas cleaning pipeline
├── dashboard/
│   └── Amazon_Dashboard.pbix
└── README.md

 Key Insights
Majority of orders are successfully Delivered, with a small percentage Cancelled/Returned — indicating healthy fulfillment performance.
Revenue shows year-over-year fluctuation, with a notable dip in 2021 before recovering through 2023.
Electronics and Sports & Outdoors are the top-performing categories by revenue.

How to Use
Clone this repository
Open dashboard/Amazon_Dashboard.pbix in Power BI Desktop
Explore the interactive slicers and cross-filtering visuals

About This Project

Built as a portfolio project to demonstrate an end-to-end data analytics workflow: Python for data preparation, Power BI for visualization and business intelligence reporting.
