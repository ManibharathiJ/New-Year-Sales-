# New Year Sales Analysis Project
## Project Overview
This project analyzes New Year sales data to uncover patterns, trends, and insights related to customer purchasing behavior. The analysis aims to help stakeholders understand which customer demographics and product categories contribute most to sales, enabling data-driven decisions for marketing and inventory planning.

## Dataset
The dataset contains detailed sales records including customer demographics, purchase details, and product categories. Key attributes include:

•	User ID, Customer Name, Product ID

•	Gender, Age Group, Age

•	Marital Status, State, Zone

•	Occupation, Product Category

•	Number of Orders, Purchase Amount

•	Order Status

The data is primarily from the New Year sales period and includes a variety of products and customer profiles.

##  Project Instructions
## Step 1: Import Libraries
•	Import essential Python libraries: numpy, pandas, matplotlib.pyplot, seaborn.

•	Use %matplotlib inline for inline visualization in notebooks.

## Step 2: Load and Explore Dataset
•	Load data from New-Year-Sales-Data.xlsx.

•	Perform initial exploration including viewing data structure and sample records.

##  Step 3: Data Cleaning
•	Inspect for null values.

•	Drop irrelevant columns not contributing to analysis.

•	Remove rows with nulls in critical columns.

•	Convert the Amount column to integer type for consistency.

##  Step 4: Data Overview and Summary
•	Generate summary statistics.

•	Check unique values in important columns to better understand data scope.

##  Exploratory Data Analysis (EDA)
## Gender Analysis

•	Question: Which gender has higher purchasing power?

•	Visuals: Count plot for gender; bar chart of total purchase amount by gender.

## Age Group Analysis

•	Question: Which age group makes the most purchases? Is there a trend in purchasing power by age?

•	Visuals: Count plot of age groups by gender; bar chart of total purchase amount by age group.

##  State Analysis

•	Question: Which states generate the highest number of orders and revenue?

•	Visuals: Bar charts for top 10 states by number of orders and total sales amount.

##  Marital Status Analysis

•	Question: How does marital status affect purchasing behavior?

•	Visuals: Count plot of marital status; bar chart of total spent by marital status with gender hue.

##  Occupation Analysis

•	Question: Which occupations contribute most to sales?

•	Visuals: Count plot for occupation; bar chart for total sales by occupation.

##  Product Category Analysis

•	Question: Which product categories are most popular and revenue-generating?

•	Visuals: Count plot of product categories; bar chart of total sales by top product categories.

## Conclusion
##  Summarize key findings from analysis.

•	Describe a typical high-purchasing customer profile based on demographics and buying patterns.

## Additional Analysis Questions (For Further Exploration)
•	Age group contribution per product category, segmented by gender.

•	Spending variation by marital status across age groups.

•	States with highest growth in orders and revenue; seasonality in sales.

•	Occupation preferences for specific product categories.

•	Correlations between age and spending, by gender.


##  Technologies Used
•	Python 3.x

•	Pandas for data manipulation

•	Matplotlib and Seaborn for data visualization

•	Jupyter Notebook or any Python IDE

##  Data Source
•	Provided New Year Sales dataset (New-Year-Sales-Data.xlsx).


