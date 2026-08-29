🛒 𝗘-𝗰𝗼𝗺𝗺𝗲𝗿𝗰𝗲 𝗦𝗮𝗹𝗲𝘀 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀


 𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄
This project presents an end-to-end E-commerce Sales Analysis using Microsoft Excel, Power Query, and Power BI.
The objective of the project is to transform raw e-commerce transaction data into a structured and interactive business intelligence solution. The project covers data preprocessing, data quality validation, calculated fields, dimensional modeling, DAX measures, and interactive dashboard development.
The final Power BI report provides insights into sales performance, products, customers, geography, payment methods, order behavior, discounts, and overall business performance.

🎯 𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗢𝗯𝗷𝗲𝗰𝘁𝗶𝘃𝗲𝘀
The main objectives of this project are to:

Clean and preprocess raw e-commerce data
Identify and handle data-quality issues
Standardize data formats and values
Create calculated fields for business analysis
Validate transaction consistency
Structure the data into fact and dimension tables
Build relationships between dimension and fact tables
Create DAX measures for KPI analysis
Develop an interactive Power BI dashboard
Analyze sales, products, customers, geography, orders, payments, and discounts
Present actionable business insights through visualizations

🛠️ Tools & Technologies

Microsoft Excel- Initial data inspection, cleaning, validation and calculated fields
Power Query- Data transformation and preparation
Power BI- Data modeling, visualization and dashboard development
DAX- Measures and analytical calculations
GitHub- Project documentation and portfolio presentation


🧹 Data Preprocessing

The raw dataset was reviewed and prepared before performing analysis.
Data Cleaning Activities
Checked for duplicate records
Reviewed missing values
Standardized data types
Standardized numerical and currency fields
Checked categorical values
Applied data validation
Applied filtering and sorting
Identified inconsistent transaction records
The cleaning process was performed with the goal of preserving valid transaction information while identifying records that required additional validation.

🧮 Calculated Columns

Additional calculated columns were created in Excel to improve data quality analysis and support business calculations.
1. Quantity Status
Used to classify quantity values and identify valid or potentially problematic quantity records.
This helps distinguish normal transaction quantities from unusual values such as zero or negative quantities.

2. Order Status Consistency
Used to identify whether the quantity and order status of a transaction are logically consistent.

3. Rating Status
Used to classify whether a transaction contains a customer rating. This allows the analysis to distinguish between: Rated,Not Rated

4. Gross Amount
Gross Amount = Unit Price × Quantity // This represents the sales amount before applying discounts.

5. Discount Amount
Discount Amount = Gross Amount × Discount %  // Calculated based on the gross amount and discount percentage.

6. Net Amount
Net Amount = Gross Amount − Discount Amount // This represents the sales value after discount.

🗂️ Data Modeling

The Power BI model was structured using a fact and dimension table approach.
𝗙𝗮𝗰𝘁 𝗧𝗮𝗯𝗹𝗲

𝗦𝗮𝗹𝗲𝘀_𝗱𝗲𝘁𝗮𝗶𝗹𝘀
Contains transactional information such as:
Order ID
Customer ID
Product ID
Quantity
Unit Price
Discount
Payment Method
Order Status
Gross Amount
Discount Amount
Net Amount

𝗗𝗶𝗺𝗲𝗻𝘀𝗶𝗼𝗻 𝗧𝗮𝗯𝗹𝗲𝘀

Product_details
Product ID
Product Name
Product Category

Location_details

Contains geographical information such as:
Location ID
Country
Shipping City
🔗 Data Model

📊 DAX Measures

Key measures created for the Power BI analysis include:
Total Net Sales
Total Orders
Total Quantity
Total Discount
Total Discount =
Average Order Value
Average Rating

📈 Power BI Dashboard

The Power BI report consists of five analytical pages.

1️⃣  Home- Sales Overview

The Home page provides a high-level summary of business performance.
KPIs
Total Sales
Total Orders
Average Rating
Discount Amount
Total Quantity
Average Order Value
Total YTD
Total Customers
Visualization
Sales by Month
Interactive Filters
Product Category
Country
Order Status
Year
The page provides an executive-level view of overall e-commerce performance.

2️⃣ Product & Category Analysis

This page focuses on product and category performance.
Visualizations
Sales by Product Category
Quantity by Category
Top 10 Products
Category Contribution
Key analytical questions
Which product categories generate the highest sales?
Which categories have the highest quantity sold?
Which products are the top performers?
What percentage of total sales does each category contribute?

3️⃣ Customer & Geography Analysis

This page analyzes geographical and customer-related performance.
Visualizations
Sales by Country
Sales by City
Orders by Country
Customer Rating Distribution
Key analytical questions
Which countries generate the most sales?
Which cities are the strongest markets?
Where are the highest numbers of orders?
What is the distribution of customer ratings?

4️⃣ Payment Analysis

This page analyzes payment behavior and order trends.
Visualizations
Sales by Payment Method
Orders by Payment Method
Monthly Order Trend
Customer Payment Method Usage
Key analytical questions
Which payment methods generate the most sales?
Which payment methods are most frequently used?
How does order volume change over time?
What is the distribution of customer payment preferences?

5️⃣ Discount & Performance Analysis

This page focuses on discounts and their relationship with sales performance.
Visualizations
Sales Before vs After Discount
Discount by Category
Sales Performance Matrix
Key analytical questions
How much sales value is reduced through discounts?
Which categories receive the highest discounts?
How do gross and net sales differ?
How does sales performance vary across categories and months?

🎛️ Dashboard Interactivity

The dashboard includes interactive controls for:
Product Category
Country
Order Status
Year
The slicers allow users to dynamically analyze the dashboard based on selected dimensions.
A reset option is also provided to return the analysis to its default filter state.
Page-navigation buttons allow users to move between different analytical sections of the report.
Bookmark allow users to move specific portion of the report.

📁 Project Structure

Ecommerce-Sales-Analysis/
│
├── Data/
│   └── ecommerce_retail_transactions_raw.xlsx
│
├── Excel/
│   └── ecommerce sales.xlsx
│
├── PowerBI/
│   └── ecommerce sales.pbix
│
├── Screenshots/
│   ├── Home.png
│   ├── Product & Category analysis.png
│   ├── Geography.png
│   ├── Payment Analysis.png
│   └── Discount & Performance Analysis.png
│
└── README.md

🔍𝗔𝗻𝗮𝗹𝘆𝘁𝗶𝗰𝗮𝗹 𝗔𝗿𝗲𝗮𝘀

The final insights should be derived from the actual dashboard results rather than assumptions.
Examples of questions addressed by the analysis include:
Which product category contributes the most to total sales?
Which products are the top performers?
Which countries and cities generate the highest sales?
Which payment methods are most commonly used?
How does order volume change over time?
Which categories receive the highest discounts?
How much do discounts affect net sales?
What is the distribution of customer ratings?
Which categories have stronger customer ratings?

📌 𝗗𝗮𝘁𝗮 𝗤𝘂𝗮𝗹𝗶𝘁𝘆 𝗖𝗼𝗻𝘀𝗶𝗱𝗲𝗿𝗮𝘁𝗶𝗼𝗻𝘀

During preprocessing, particular attention was given to transaction records containing unusual values.
Examples:
Zero quantities
Negative quantities
Missing ratings
Order-status inconsistencies
Records requiring validation
Instead of automatically deleting every unusual value, additional status fields were created to identify and evaluate these records.
This approach helps distinguish between data-quality issues and potentially meaningful business transactions, such as returns or adjustments.

📚 𝗦𝗸𝗶𝗹𝗹𝘀 𝗗𝗲𝗺𝗼𝗻𝘀𝘁𝗿𝗮𝘁𝗲𝗱

This project demonstrates practical skills in:
Data Cleaning
Data Preprocessing
Data Validation
Excel
Power Query
Data Transformation
Dimensional Modeling
Data Relationships
DAX
KPI Development
Data Visualization
Dashboard Design
Business Analysis
GitHub Project Documentation
