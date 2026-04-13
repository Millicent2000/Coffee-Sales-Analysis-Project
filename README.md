# Coffee-Sales-Analysis-Project
## Table of content

- [Project Overview](#project-overview)

- [Description of Data Source](#description-of-data-source)
  
- [Tools](#tools)
  
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)

- [Exploratory Data Analysis](#exploratory-data-analysis)

- [Data Analysis](#data-analysis)
  
- [Findings](#findings)

- [Recommendations](#recommendations)
  
- [Limitations](limitations)

- [Reference](#reference)


### Project Overview

This project focuses on analyzing coffee sales data to uncover trends in customer purchasing behavior, product performance, and revenue generation. An interactive dashboard was developed to enable dynamic exploration of sales performance across different dimensions such as time, product type, and customer segments.


<img width="611" height="506" alt="sales overtime" src="https://github.com/user-attachments/assets/b994abc9-b0dc-447d-b886-05a64d8b5bad" />

<img width="517" height="406" alt="country" src="https://github.com/user-attachments/assets/10e5c6da-273d-4801-b0bb-da6dbf617d0c" />

<img width="543" height="406" alt="top 5 countries" src="https://github.com/user-attachments/assets/3cf42190-8b32-40a3-bb66-046ff77fa08c" />




### Description of Data Source

The dataset consists of multiple related tables, including:
Orders data (transaction-level details)
Customers data (customer information such as name, email, country)
Products data (coffee type, roast type, size, and pricing)
Data was distributed across different tables and required integration to create a unified dataset suitable for analysis.

### Tools

- Microsoft Excel
  - Pivot Tables
  - Pivot Charts
  - Slicers & Timeline
  - Functions: XLOOKUP, IF
  - Data formatting & cleaning tools
 
 ### Data Cleaning and Preparation

    Several preprocessing steps were performed to ensure data quality and usability:

- Used XLOOKUP to merge datasets and retrieve:
  - Customer Name
  - Email
  - Country
  - Coffee Type
  - Roast Type
  - Size
  - Unit Price
- Created Sales column using:
 - Sales = Unit Price × Quantity
- Handled missing data:
- Used IF function to replace blank email values
- Filled missing fields via lookup functions
- Standardized and formatted data:
- Converted date column into proper format
- Formatted Unit Price and Sales as currency
- Customized Size column formatting
- Replaced abbreviations with full descriptive names
- Data validation:
- Checked and removed duplicates
  
### Exploratory Data Analysis
Initial exploration was conducted to understand patterns and distributions:
- Examined sales trends over time
- Identified top-performing customers
- Analyzed product variations:
  - Coffee type
  - Roast type
  - Size
- Compared customer segments:
  - Loyalty card holders vs non-holders
 
### Data Analysis

An interactive dashboard was built to analyze key metrics:
- 📈 Line Chart: Sales over time by coffee type
- 🏆Bar Chart: Top 5 customers by total purchases
- 🧭 Timeline Filter: Enables time-based analysis
- 🎛️ Slicers:
  - Roast Type (Dark, Medium, Light)
  - Coffee Size (0.2kg, 0.5kg, 1.0kg, 2.5kg)
  - Loyalty Card Status (Yes/No)
    
These features allow users to dynamically filter and explore insights.

### Findings
- Sales trends vary over time, with noticeable peaks in certain periods
- Certain coffee types and roast levels perform better than others
- A small group of top customers contributes significantly to total revenue
- Customers with loyalty cards show stronger purchasing behavior
- Product size influences purchasing patterns and revenue contribution

### Recommendations
- 🎯 Target top customers with personalized offers or rewards
- 💳 Promote loyalty programs to increase repeat purchases
- 📦 Focus on high-performing product sizes and roast types
- 📅 Use seasonal trends to plan promotions and inventory
- 🌍 Expand marketing strategies in countries with high sales performance
  
### Limitations
- Data was sourced from multiple tables, increasing risk of lookup errors
- Missing data required assumptions and manual handling
- Analysis is limited to available variables (no demographic depth beyond country)
- No external factors (e.g., seasonality drivers, marketing campaigns) included
  
### Reference
This project was inspired by the tutorial below:

[https://youtu.be/m13o5aqeCbM?si=56GRmPhPdeu06M_o]

While the tutorial provided the foundation, I independently handled data cleaning, analysis, and dashboard creation, adding my own insights and improvements.
  
