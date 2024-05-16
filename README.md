# Bank Loan Data Analysis Project

## Project Overview

This project focuses on analyzing and visualizing bank loan data to derive meaningful insights and support data-driven decision-making. The project involves creating a comprehensive Bank Loan Report, including key performance indicators (KPIs), visual representations, and detailed loan data analysis.

### Techstack

1. Excel
2. Tableau
3. SQL

### Files and Directories

- `Bank Loan Dashboard.twb`: Tableau workbook containing the dashboards and visualizations.
- `Bank Loan DB.db`: SQLite database containing the loan data.
- `Bank Loan DB.sqbpro`: SQLite database project file for managing the database.
- `BANK LOAN DOMAIN REPORT.docx`: Document providing domain knowledge and background information about bank loans.
- `BANK LOAN REPORT QUERY DOCUMENT.docx`: Document with SQL queries used for data extraction and analysis.
- `DATA TERMINOLOGIES.docx`: Document defining the terminologies and fields used in the data.
- `financial_loan.csv`: CSV file containing the financial loan data.
- `PROBLEM STATEMENT.docx`: Document outlining the problem statement and project objectives.

## Project Objectives

1. **Monitor and Assess Lending Activities**: Track the bank's lending performance through key metrics and trends.
2. **Data-Driven Decision Making**: Support decision-making with comprehensive data analysis and visualizations.
3. **Identify Trends**: Analyze trends in loan applications, funded amounts, and repayments to inform lending strategies.

### Key Performance Indicators (KPIs)

#### Summary Dashboard

- **Total Loan Applications**: Total number of loan applications received.
- **MTD Loan Applications**: Month-to-date loan applications.
- **Total Funded Amount**: Total amount of funds disbursed as loans.
- **MTD Total Funded Amount**: Month-to-date funded amount.
- **Total Amount Received**: Total amount received from borrowers.
- **MTD Total Amount Received**: Month-to-date amount received.
- **Average Interest Rate**: Average interest rate across all loans.
- **MTD Average Interest Rate**: Month-to-date average interest rate.
- **Average Debt-to-Income Ratio (DTI)**: Average DTI of borrowers.

#### Good Loan vs. Bad Loan KPIs

- **Good Loan Application Percentage**: Percentage of loans classified as 'Good Loans' (Fully Paid or Current).
- **Good Loan Applications**: Total number of 'Good Loan' applications.
- **Good Loan Funded Amount**: Total funded amount for 'Good Loans'.
- **Good Loan Total Received Amount**: Total amount received for 'Good Loans'.
- **Bad Loan Application Percentage**: Percentage of loans classified as 'Bad Loans' (Charged Off).
- **Bad Loan Applications**: Total number of 'Bad Loan' applications.
- **Bad Loan Funded Amount**: Total funded amount for 'Bad Loans'.
- **Bad Loan Total Received Amount**: Total amount received for 'Bad Loans'.

#### Loan Status Grid View

- **Loan Status**: Breakdown of loans by status (Fully Paid, Current, Charged Off, etc.).
- **Total Loan Applications**: Total number of loan applications by status.
- **Total Funded Amount**: Total funded amount by status.
- **Total Amount Received**: Total amount received by status.
- **MTD Funded Amount**: Month-to-date funded amount by status.
- **MTD Amount Received**: Month-to-date amount received by status.
- **Average Interest Rate**: Average interest rate by status.
- **Average DTI**: Average DTI by status.

#### Overview Dashboard

- **Monthly Trends by Issue Date**: Line chart showing trends in loan applications, funded amounts, and received amounts.
- **Regional Analysis by State**: Filled map displaying loan metrics by state.
- **Loan Term Analysis**: Donut chart showing loan statistics by term length.
- **Employee Length Analysis**: Bar chart showing loan metrics by employment length.
- **Loan Purpose Breakdown**: Bar chart showing loan metrics by loan purpose.
- **Home Ownership Analysis**: Tree map displaying loan metrics by home ownership status.

![SUMMARY](/Users/shehbazpatel/Documents/Ineuron_Projects/Data_analyst_Project/Tableau_image/summary.jpg)

(https://drive.google.com/file/d/1TE5ezJQirCMCr8lN0deRWsZBFVIm8siA/view?usp=share_link)

(https://drive.google.com/file/d/13yhFXrs4OpWA4yZ5w4rEWXzQ8Zn6yUG5/view?usp=share_link)

### Data Sources

The project uses data from various sources including:

- **Loan Applications**: Detailed applications submitted by borrowers.
- **Credit Reports**: Credit history and scores accessed from credit bureaus.
- **Internal Records**: Bank's internal records of loan transactions.
- **Online Portals**: Data collected from the bank's online platforms.
- **Third-party Data Sources**: External services for income verification and other data.

### SQL Queries

The SQL queries used for data extraction and analysis are detailed in the `BANK LOAN REPORT QUERY DOCUMENT.docx`. These queries cover various KPIs, good vs. bad loan metrics, and loan status breakdowns.

### Instructions

1. **Database Setup**: Import the `financial_loan.csv` into the SQLite database `Bank Loan DB.db`.
2. **SQL Queries**: Use the SQL queries provided in the `BANK LOAN REPORT QUERY DOCUMENT.docx` to extract and analyze data.
3. **Data Visualization**: Open the Tableau workbook `Bank Loan Dashboard.twb` to view and interact with the visualizations.
4. **Documentation**: Refer to the domain knowledge and data terminologies documents for detailed explanations of the data fields and context.

## Conclusion

This project provides a comprehensive analysis of bank loan data, enabling stakeholders to monitor lending activities, assess loan performance, and make informed decisions based on data-driven insights. The dashboards and reports facilitate a clear understanding of key metrics and trends, supporting strategic planning and risk management.
