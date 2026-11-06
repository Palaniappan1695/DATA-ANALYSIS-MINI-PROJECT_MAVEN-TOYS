🧸 Maven Toys – End-to-End Sales Analysis | Power BI



📌 Project Overview

Maven Toys is a retail toy business operating across multiple stores and selling different categories of products.

This project focuses on performing an end-to-end retail sales analysis using Microsoft Excel, Power Query and Power BI.

The objective is to transform raw business data into a structured analytical model and develop an interactive dashboard that provides insights into sales performance, product profitability, store performance and monthly sales trends.

The project follows the complete data analytics workflow, starting from raw data preparation and ending with business insights and recommendations.

🎯 Business Problem

Retail businesses generate large volumes of transaction data, but raw data alone does not provide meaningful business insights.

Management needs answers to questions such as:

How much revenue is the business generating?

What is the total profit and profit margin?

Which product categories contribute the most to revenue?

Which stores and cities perform better?

How does sales performance change over time?

Which products and locations require further attention?

How can sales and inventory planning be improved?

This project addresses these questions through data transformation, analysis and visualization.

🎯 Project Objectives

Prepare and clean raw retail datasets.

Integrate sales, product, store, inventory and calendar information.

Develop a structured data model.

Create business KPIs using DAX.

Analyse revenue, costs and profitability.

Identify product category and store performance.

Understand monthly sales trends.

Present findings through an interactive Power BI dashboard.

🛠️ Tools & Technologies

Technology

Application

Microsoft Excel

Data inspection and initial preparation

Power Query

Data cleaning, transformation and merging

Power BI

Data modelling and dashboard development

DAX

Calculated measures and business KPIs

Data Visualization

Business performance reporting

📂 Dataset Structure

The project consists of six datasets.

Dataset

Description

Sales

Individual sales transactions, dates, products, stores and units sold

Products

Product IDs, categories, costs and selling prices

Stores

Store IDs, store details and geographical information

Inventory

Product stock information across stores

Calendar

Date dimension for time-based analysis

Data Dictionary

Field definitions and dataset descriptions

Data Integration

The datasets were connected to create a consolidated analytical model.

The Sales dataset was enriched with product, store and calendar information through Power Query merges.

The Inventory dataset was also validated using store and product identifiers.

🔄 Project Workflow

Step 1 – Data Understanding

Imported the available Excel datasets.

Reviewed the structure and columns of each dataset.

Understood the relationships between sales, products, stores, inventory and calendar data.

Identified important business fields and analytical requirements.

Step 2 – Data Cleaning Using Power Query

Performed data preparation and transformation activities:

Removed unnecessary spaces and formatting inconsistencies.

Cleaned currency values in product cost and selling price columns.

Converted numerical fields into appropriate data types.

Standardized date formats using locale settings.

Checked missing and unmatched records.

Validated product, store and date identifiers.

Step 3 – Data Transformation

Merged Sales with Products using Product_ID.

Merged Sales with Stores using Store_ID.

Connected Sales with Calendar using Date.

Validated Inventory using Store_ID and Product_ID.

Created additional calculated columns for revenue, product cost and profit analysis.

Prepared the final analytical dataset.

Step 4 – Data Validation

Performed data quality checks to ensure the accuracy of the integrated datasets.

Validated merge results.

Checked unmatched records.

Verified date conversions.

Reviewed calculated fields.

Confirmed the consistency of key identifiers.

Step 5 – Data Modelling in Power BI

Loaded all six datasets into Power BI.

Established relationships between the relevant tables.

Reviewed relationship cardinality and filter directions.

Created a structured model for reporting and analysis.

Step 6 – DAX Measures and KPI Development

Developed business measures to calculate key performance indicators, including:

Total Revenue

Total Product Cost

Total Profit

Profit Margin

These measures form the foundation of the dashboard's financial performance analysis.

📊 Dashboard & Business Analysis

The Power BI dashboard focuses on the following analytical areas:

1. Overall Business Performance

Analysed the company's overall financial performance using KPI cards.

Total Revenue

Total Product Cost

Total Profit

Profit Margin

2. Product Category Analysis

Compared product categories to understand:

Revenue contribution.

Profit contribution.

Product category performance.

Differences between revenue and profitability.

3. Store & City Performance

Evaluated geographical business performance by analysing:

Revenue across cities.

Store-wise sales performance.

Differences in store contributions.

Opportunities to investigate underperforming locations.

4. Monthly Sales Trend

Analysed historical monthly sales performance to:

Understand revenue movements.

Identify higher and lower sales periods.

Observe changes in monthly performance.

Establish a foundation for future sales forecasting.

💡 Key Business Insights & Recommendations

The dashboard provides a foundation for identifying business opportunities.

Potential management recommendations include:

Monitor high-revenue and high-profit product categories.

Investigate categories with high revenue but relatively low profit margins.

Compare store performance to identify locations requiring improvement.

Use historical sales trends to support revenue forecasting.

Monitor inventory requirements based on product sales performance.

Review product pricing and cost structures to improve profitability.

📈 Expected Business Value

This project demonstrates how raw retail data can be transformed into meaningful business information.

It supports management in:

Monitoring financial performance.

Understanding revenue and profitability.

Comparing product and store performance.

Identifying business improvement opportunities.

Supporting inventory and sales planning.

Making data-driven decisions.

🚀 Skills Demonstrated

Excel Data Preparation

Data Cleaning

Power Query ETL

Data Transformation

Data Integration

Data Modelling

DAX Calculations

KPI Development

Power BI Dashboard Development

Data Visualization

Retail Sales Analysis

Business Intelligence

Business Problem Solving



👨‍💻 Author

Palaniappan

Finance Professional | Aspiring Data Analyst

Interested in applying data analytics and business intelligence to solve real-world business problems.

Technical Interests: Microsoft Excel | Power BI | SQL | Python | Data Analytics
5. Profitability Analysis

Examined the relationship between revenue, product costs and profit to understand the company's profitability across product categories and stores.
