# Coffee-Sales-Analysis-Project

### Project Overview

This project focuses on analyzing coffee sales data to uncover trends in customer purchasing behavior, product performance, and revenue generation. An interactive dashboard was developed to enable dynamic exploration of sales performance across different dimensions such as time, product type, and customer segments.

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
  
### Exploratory Data Analysis (EDA)
Initial exploration was conducted to understand patterns and distributions:
- Examined sales trends over time
- Identified top-performing customers
- Analyzed product variations:
  - Coffee type
  - Roast type
  - Size
- Compared customer segments:
  - Loyalty card holders vs non-holders
 
###
