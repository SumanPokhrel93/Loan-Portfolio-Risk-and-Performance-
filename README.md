## Loan Portfolio Risk and Performance

### Project Overview
This project analyses a loan portfolio dataset using Python, SQL and Tableau to understand loan performance, borrower risk, interest rate patterns and portfolio distribution. The dataset originally contained 55 columns and required cleaning before analysis.

The main objective of this project is to identify key risk and performance indicators such as total loan amount issued, average interest rate, loan status distribution, high-risk loan purposes, debt-to-income risk groups, income-based loan patterns and loan performance by term.

## Tools Used
- Python – used for data cleaning, preprocessing and exporting the cleaned dataset
- DBeaver – used as the database management tool to import the cleaned CSV file into PostgreSQL and manage database tables
- PostgreSQL – used as the relational database for storing and querying the loan data
- SQL – used to perform loan portfolio analysis, risk calculations and business queries
- Tableau – used to build the final dashboard and visualise key insights
- GitHub – used for project documentation and portfolio presentation

## About the Dataset
The dataset contains loan-related information such as: Loan amount, Interest rate, Loan status, Loan purpose, Loan grade, Annual income, Debt-to-income ratio, Loan term, Borrower state.

### Data Cleaning
Python was used to clean and prepare the dataset. The cleaning process included:
- Checking the shape, columns and data types
- Identifying missing values
- Removing unnecessary columns
- Cleaning columns into a clean format
- Creating loan status groups such as Good, Bad and Active
- Exporting the cleaned dataset for analysis

### SQL Analysis Questions
The following business questions were answered using SQL:
- What is the total loan amount issued?
- What is the average interest rate?
- What percentage of loans are Good, Bad or Active?
- Which loan purpose has the highest loan amount?
- Which loan grade has the highest interest rate?
- Which loan purpose has the highest bad-loan percentage?
- Which debt-to-income group has the highest bad-loan rate?
- Which income group receives the largest average loans?
- Which states have the highest loan volume?
- Comparing 36-month and 60-month loans, which has the higher bad-loan percentage?

## Key Findings
- The total loan amount issued was approximately $163.62 million.
- The average interest rate was approximately 12.43%.
- Most loans were classified as Active, representing around 94.42% of the portfolio.
- Bad loans represented around 1.11% of total loans.
- Debt consolidation had the highest total loan amount among all loan purposes.
- Loan grade G had the highest average interest rate at around 30.80%.
- Among loan purposes, house loans showed the highest bad-loan percentage in the analysis.
- The Low DTI group showed the highest bad-loan percentage at around 1.70%.
- High-income borrowers received the largest average loan amount.
- California (CA) had the highest loan count and total loan amount among states.
- 60-month loans had a higher bad-loan percentage than 36-month loans, suggesting that longer-term loans may carry higher repayment risk.

## Recommendations for Decision Makers
- Review higher-risk loan purposes
  Loan purposes with higher bad-loan percentages should be reviewed more carefully before approval.
- Monitor lower loan grades closely
  Lower loan grades had higher average interest rates, which may indicate higher borrower risk.
- Assess long-term loans carefully
  60-month loans showed a higher bad-loan percentage than 36-month loans, so longer-term loans may require stronger risk checks.
- Use income and DTI groups for risk assessment
  Borrower income and debt-to-income groups should be considered when evaluating loan affordability and repayment ability.
- Focus on state-level portfolio concentration
  States with the highest loan amounts should be monitored to avoid over-concentration in specific geographic areas.

## Tableau Dashboard
A Tableau dashboard was created to present the main loan portfolio insights visually. The dashboard includes:
- Total Loan Amount KPI
- Average Interest Rate KPI
- Bad Loan Percentage KPI
- Top 5 Loan Amount by Loan Purpose
- Average Interest Rate by Grade
- Top 5 Bad Loan Percentage by Purpose
- Top 10 States by Loan Amount
- Average Loan Amount by Income Group
- Interactive Filters for Loan Purpose and State

## Skills Demonstrated
This project demonstrates the following data analyst skills:
- Data cleaning using Python
- SQL aggregation and filtering
- CASE statements for grouping
- Percentage calculations in SQL
- Risk-based business analysis
- Data visualisation using Tableau
- Dashboard design
- Portfolio documentation using GitHub
- Conclusion

This project shows how Python, SQL and Tableau can be used together in an end-to-end data analysis workflow. Python was used to clean and prepare the raw loan data, SQL was used to answer business and risk-related questions, and Tableau was used to build a dashboard for presenting the key findings.

## Attachments
- Dataset : [Link](https://www.openintro.org/data/index.php?data=loans_full_schema)
- Python Notebook: [Jupyter](http://localhost:8888/notebooks/Loan_analysis.ipynb?)


