# Customer Analytics Data Analytics Project

## Project Overview

This project is a Customer Analytics project developed as part of the **Internnova Data Analytics Internship – Week 6 Final Capstone Project**.

The project analyzes customer behavior, spending patterns, subscription types, acquisition channels, customer lifetime value, and churn to generate useful business insights and support data-driven decision-making.

## Problem Statement

Businesses need to understand customer behavior and value to improve revenue, customer retention, marketing effectiveness, and overall decision-making.

This project analyzes customer data to identify important patterns, trends, customer segments, and business opportunities.

## Objective

The main objectives of this project are to:

* Clean and prepare customer data.
* Perform Exploratory Data Analysis (EDA).
* Identify important trends and relationships.
* Create meaningful data visualizations.
* Develop an interactive Power BI dashboard.
* Generate business insights and recommendations.
* Demonstrate an end-to-end data analytics workflow using Git and GitHub.

## Dataset Description

The project uses a customer analytics dataset containing **15,025 records and 20 columns after data preparation**.

Important fields include:

* Customer_ID
* Order_Date
* Age
* Gender
* City
* Subscription_Type
* Acquisition_Channel
* Product_Category
* Total_Orders
* Total_Spending
* Average_Order_Value
* Discount_Percentage
* Website_Visits
* Avg_Session_Duration_Min
* Satisfaction_Score
* Support_Tickets
* Refund_Requests
* Premium_Customer
* Churn_Status
* Customer_Lifetime_Value

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* SQL
* Excel
* Power BI
* Git
* GitHub

## Data Cleaning Process

The dataset was inspected and prepared before analysis.

The main cleaning steps were:

1. Checked the dataset structure and data types.
2. Identified missing values.
3. Filled missing numeric values using the median.
4. Filled missing Gender values using the mode.
5. Checked for duplicate records.
6. Removed duplicate records where required.
7. Verified the cleaned dataset.
8. Saved the final cleaned dataset as `customer_analytics_cleaned.csv`.

## Exploratory Data Analysis

Exploratory Data Analysis was performed to understand customer behavior and identify important patterns.

The analysis included:

* Dataset overview
* Descriptive statistics
* Correlation analysis
* Outlier analysis
* Product category performance
* Subscription performance
* Acquisition channel performance
* Customer spending
* Customer lifetime value
* Churn-related patterns

## Data Visualizations

Five major visualizations were created:

1. **Total Spending by Product Category**
2. **Customer Count by Subscription Type**
3. **Customers by Acquisition Channel**
4. **Age Distribution of Customers**
5. **Total Spending vs Customer Lifetime Value**

These visualizations help communicate customer behavior and business performance clearly.

## Power BI Dashboard

An interactive **Customer Analytics Dashboard** was developed using Power BI.

### Key Performance Indicators

* Total Customers
* Total Spending
* Average Customer Lifetime Value

### Dashboard Visualizations

* Total Spending by Product Category
* Customers by Subscription Type
* Customers by Acquisition Channel
* Total Spending vs Customer Lifetime Value
* Customer Churn Status

### Dashboard Slicers

* Subscription Type
* Product Category
* Gender
* Churn Status

The dashboard allows users to interactively filter and analyze customer data.

## Key Business Insights

1. Product categories differ in their contribution to total customer spending, helping identify stronger and weaker revenue areas.

2. Subscription types show differences in customer count, spending, and customer lifetime value. Higher-value subscription segments can provide opportunities for retention and upselling.

3. Acquisition channels contribute differently to customer volume and spending. Strong-performing channels can therefore receive greater marketing attention.

4. Churn status can be analyzed together with spending and customer lifetime value to identify valuable customers who may be at risk of leaving.

5. Total orders, total spending, and customer lifetime value are important indicators of customer value and purchasing behavior.

## Business Recommendations

1. **Focus marketing investment on high-performing acquisition channels and product categories** identified through the analysis and Power BI dashboard.

2. **Develop targeted retention and loyalty campaigns** for high-value customers and customers showing churn risk.

3. Use customer spending and lifetime value to create customer segments and provide more personalized offers.

## Project Workflow

1. Data collection
2. Git and GitHub setup
3. Data cleaning and preparation
4. Exploratory Data Analysis
5. Data visualization
6. Power BI dashboard development
7. Business insights and recommendations
8. Project documentation and presentation

## Repository Contents

The repository contains the project dataset, cleaned dataset, analysis outputs, visualizations, dashboard file, documentation, and supporting project files.

Important files include:

* `customer_analytics_dataset.csv`
* `customer_analytics_cleaned.csv`
* `correlation_matrix.csv`
* `outlier_counts.csv`
* `EDA_findings.txt`
* Visualization PNG files
* `visualization_findings.txt`
* `business_insights.txt`
* Power BI dashboard file
* `README.md`

## Conclusion

This project demonstrates an end-to-end data analytics workflow, beginning with data preparation and Git/GitHub version control and continuing through EDA, visualization, Power BI dashboard development, and business recommendations.

The project demonstrates how customer data can be transformed into meaningful insights that support data-driven business decisions related to customer value, marketing, revenue, and retention.

## Internship

**Internnova Data Analytics Internship – Week 6 Final Capstone Project**

## GitHub Repository

`https://github.com/cgayatri004-collab/final-data-analytics-project`
