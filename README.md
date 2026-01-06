# Data-Analytics-Banking-Domain-Dashboard

🎯 Banking Dashboard Project Explanation (Detailed Version)
1. Project Overview

This is my Banking Domain Dashboard Project built using Excel and Power BI.
The main purpose of this dashboard is to analyze the bank’s performance in terms of Loans, Deposits, and Client Growth, and to help management make data-driven decisions quickly.

2. Data Preparation (Excel)

I started the project by collecting raw banking data in Excel.
The first step was data cleaning, where I:

Removed duplicate records

Fixed inconsistent formats (like dates and text cases)

Checked for missing values and corrected them

Verified that all numeric columns had the right data type (for example, loan amount as a number, not text).

This helped me make sure that the data was accurate, consistent, and ready for analysis.

3. Data Transformation (Power Query in Power BI)

Next, I imported the cleaned data into Power BI using Power Query Editor.
Inside Power Query, I performed several transformation steps:

Changed data types where needed (for example, date columns and currency columns).

Used options like Replace Values, Merge Queries, and Remove Columns to structure the data.

Used Group By to calculate key summaries like total deposits and total loans per category.

After transformation, I loaded the data into Power BI Model.

4. Data Modeling

In the data model, I defined relationships between different tables such as:

Client table

Loan table

Deposit table

Branch/Region table

I followed the Star Schema model, where the fact table contains numeric data (like loan amount, deposit amount) and the dimension tables store details (like branch, gender, occupation, year).

5. DAX Calculations and Measures

I created several DAX measures to calculate business KPIs such as:

Total Clients

Total Loan

Total Deposit

Total Business Lending

Saving Account Amount

Checking Account Amount

Total Fees and Credit Card Balance

I also created calculated measures like Loan-to-Deposit Ratio to compare performance.

6. Dashboard Design (Visualization)

I designed three main dashboards:

🏠 Home / Summary Dashboard:

Shows the overall banking performance summary.

KPIs include Total Clients, Total Loan (4.38bn), Total Deposit (3.77bn), and Business Lending (2.60bn).

Filters by Year and Gender for dynamic insights.

💰 Loan Analysis Dashboard:

Focuses on bank loan performance.

Visuals show:

Loan by Branch (BR)

Loan by Occupation

Loan by Income Band (Low, Medium, High)

Loan by Nationality

Helps understand which client groups or regions are performing well in loans.

🏦 Deposit Analysis Dashboard:

Focuses on deposits and savings trends.

Shows deposit distribution by:

Banking relationship (Commercial, Institutional, Private, Retail)

Occupation

Income Band

Nationality

KPIs include Total Deposit, Bank Deposit, and Savings/Checking Account amounts.

7. Insights from Dashboard

The bank’s Total Loan is 4.38 billion, and Total Deposit is 3.77 billion, showing active loan business.

Private Bank clients contribute the highest to both loans and deposits.

Medium income band clients have the highest share of deposits and loans.

European clients dominate both loan and deposit categories.

The dashboard allows management to filter by year, gender, and banking type to get customized insights.

8. Final Conclusion

This dashboard provides a comprehensive financial overview of the bank.
It helps stakeholders quickly analyze:

Total business growth

Client segmentation

Deposit and loan performance

Customer demographic insights

By using this dashboard, decision-makers can track performance, identify key trends, and improve financial planning effectively.
