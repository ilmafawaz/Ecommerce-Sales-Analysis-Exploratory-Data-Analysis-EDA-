# Ecommerce-Sales-Analysis-Exploratory-Data-Analysis-EDA-Intermediate Project
This project performs Exploratory Data Analysis on an Ecommerce Sales Dataset, focusing on understanding customer behavior, product performance, sales trends, revenue patterns, and the relationships between key sales variables.
The goal is to transform raw, messy data into useful insights through cleaning, visualisation, and statistical exploration.

📁 Dataset
The dataset used for this analysis is:
Ecommerce Sales Dataset (superstore_cleaned.csv)
The cleaned dataset file is uploaded here.

It includes variables such as:
Order ID
Customer ID
Product Category
Quantity
Price
Payment Method
Order Date / Shipment Date
Order Status
Geography fields (optional depending on your dataset)
Revenue-related attributes

Project Objectives
Clean and prepare the dataset
Fix missing values and incorrect types
Analyse single variables (univariate)
Explore relationships between variables (bivariate)
Extract patterns in sales, revenue, and customer purchasing behavior
Generate clear, easy-to-interpret visual insights

1. Data Cleaning
The dataset required several preparation steps, including:
Handling missing values
Converting order dates to proper datetime formats
Fixing inconsistent categories (capitalization, spacing, naming)
Removing duplicates
Creating new features where needed (for example: Total Amount = Quantity × Price)
Filtering out irrelevant or invalid entries

All cleaning steps are documented in the notebook.

2. Univariate Analysis
Single-variable analysis was performed to understand overall distributions and patterns.

Key charts include:
Product Category distribution
Price distribution
Sales distribution
Order Status count
Discount distribuition 
Each chart includes a written insight describing what the distribution reveals.

3. Bivariate Analysis
Relationships between variables were examined to uncover deeper patterns.
Examples include:
Sales vs Profit
Sales bt Region and Category
Time-based sales trends
Average Profit margin by category 
Each visualisation is followed by a detailed explanation of what the relationship indicates.

4. Key Insights Summary
Some of the major findings from the analysis:
Certain product categories contribute disproportionately to revenue
Price and quantity relationships reveal high-value and low-value purchase clusters
Despite relying primarily on numerous low-value transactions, the company significantly benefits from occasional large-value orders that enhance total revenue.
Customer buying behavior varies predictably by category and season 
Order Status analysis highlights operational strengths or delays

These insights help identify which products and customers drive the business.

The analysis provides a structured view of ecommerce performance, highlighting profitable product segments, common purchase behaviors, and key variables affecting revenue.
The cleaned dataset and visual insights support decision-making for:
Inventory planning, Marketing strategies, Customer segmentation, Revenue forecasting and Product optimisation
This intermediate project serves as a strong foundation for more advanced analytics like customer clustering, recommendation systems, or time-series forecasting.
