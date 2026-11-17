1. Data Source

The project uses a financial dataset containing business information related to sales, products, countries, business segments, costs and profitability.

Source file: Financial Sample.csv
source 
https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download

Key fields: Date, Country, Product, Segment, Sales, Gross Sales, Discounts, COGS and Profit.

2. Data Cleaning – Power Query

The dataset was examined and prepared using Power Query.

The following data quality checks and cleaning activities were performed:

Data type validation: Checked and assigned appropriate data types to date
Data Replacement:- Replaced country name with its short name for space saving


3. Data Transformation

The data was transformed to support financial analysis and reporting.

Used Power Query to prepare and organize the dataset.

Ensured date fields were suitable for time-based analysis.

Prepared numerical fields for sales, cost and profit calculations.

Created a dedicated date table using DAX 

Established the required data relationships for reporting.

4. Data Modelling

A structured data model was prepared to support interactive reporting.

Configured relationships between the financial dataset and date table.

Used the date table for year-wise and month-wise analysis

Organized the model to support DAX calculations and dashboard filtering.

5. DAX Measures

Created calculated measures to evaluate business and financial performance, including:

Total Sales

Total Profit

Profit Margin

Previous Year Sales

Year-over-Year Sales Growth

Previous Year Profit

Refer to DAX_Measures.md for the calculations.

6. Final Outcome

The data preparation and modelling process produced an analysis-ready dataset for developing an interactive Power BI dashboard that enables users to examine sales performance, profitability, product contribution, country-wise performance and business segment trends.