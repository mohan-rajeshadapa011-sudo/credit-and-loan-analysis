# credit-and-loan-analysis
🏦 Loan Portfolio Analysis using SQL & Power BI
📌 About the Project

This project focuses on analyzing a bank's loan portfolio to understand lending patterns, repayment behavior, and portfolio risk.

Using Microsoft SQL Server, I explored loan-level data and converted raw records into meaningful business metrics. The analysis covers loan volume, funding, repayments, borrower characteristics, and loan performance.

A Power BI dashboard was also created to make the analysis easier to explore through interactive visuals and KPIs.

🎯 What I Wanted to Analyze

The analysis was designed around a few key areas:

Overall size and activity of the loan portfolio

Loan repayment and performance

Difference between performing and charged-off loans

Changes in lending activity over time

Borrower and loan characteristics

Distribution of loans across states

Relationship between loan purpose and funding

Impact of loan terms and employment history on portfolio distribution

🗂️ Data Used

The dataset contains information about individual loan accounts and borrowers.

Some of the important columns include:

loan_id

loan_amount

funded_amount

total_payment

loan_status

issue_date

term

int_rate

installment

annual_income

dti

grade

sub_grade

purpose

home_ownership

emp_length

address_state

📊 Portfolio Metrics

I created SQL-based metrics to get a quick view of the portfolio, including:

Metric	Purpose
Loan Applications	Measures overall loan volume
Funded Amount	Measures total capital issued
Amount Received	Tracks borrower repayments
Average Interest Rate	Shows portfolio interest-rate level
Average DTI	Provides borrower debt-burden context
Good Loan %	Measures performing-loan share
Bad Loan %	Measures charged-off loan share
🔍 Analysis Performed
1. Loan Performance

Loans were grouped by their current status to examine differences in:

Loan count

Funded value

Payments received

Interest rates

Borrower DTI

For portfolio-level classification, Current and Fully Paid loans were treated as performing loans, while Charged Off loans were analyzed separately.

2. Time-Based Analysis

I analyzed loan activity by month to identify changes in:

Application volume

Funding

Repayments

I also included MTD and previous-MTD comparisons for period-over-period monitoring.

3. Geographic Analysis

State-level analysis was performed to understand where loan activity is concentrated.

The analysis considers:

Number of loans

Funded amount

Amount received

4. Loan Characteristics

The portfolio was segmented using different loan attributes:

Loan Term

Employment Length

Loan Purpose

Home Ownership

Grade and Sub-Grade

This makes it possible to examine how the composition of the portfolio changes across borrower and loan categories.

🧮 SQL Work

The analysis was developed primarily in SQL Server.

Some of the SQL techniques used include:

SELECT
WHERE
GROUP BY
ORDER BY
CASE
COUNT()
SUM()
AVG()


I also worked with:

Date-based calculations

Conditional aggregation

Percentage calculations

Category-wise aggregation

KPI queries

Monthly trend analysis

Comparative period analysis

📈 Dashboard

The SQL results were used to create a Power BI dashboard for exploring the portfolio interactively.

Dashboard Includes

Portfolio KPI cards

Good vs Bad Loan analysis

Loan-status breakdown

Monthly loan trends

State-wise analysis

Purpose-wise analysis

Term distribution

Employment-length analysis

Home-ownership analysis

Preview

Add your dashboard image here:

Images/
└── loan_dashboard.png


Then display it in GitHub using:

![Loan Portfolio Dashboard](Images/loan_dashboard.png)

🛠️ Technology Stack
Tool	Usage
SQL Server	Data analysis and KPI calculations
SSMS	SQL development and query execution
Power BI	Dashboard and visualization
Excel / CSV	Source data
📁 Repository Structure
Loan-Portfolio-Analysis/
│
├── Dataset/
│   └── bank_loan_data.csv
│
├── SQL/
│   └── Loan_Analysis.sql
│
├── PowerBI/
│   └── Loan_Dashboard.pbix
│
├── Images/
│   └── loan_dashboard.png
│
└── README.md

📌 Key Takeaways

The project provides a structured way to examine a lending portfolio from multiple perspectives.

The analysis connects loan volume, funding, repayment, borrower characteristics, and loan status to provide a clearer picture of portfolio composition and performance.

🚀 Possible Extensions

Some areas that can be explored in future versions:

Risk analysis by grade and sub-grade

Default-rate analysis

Advanced SQL window functions

Cohort-based repayment analysis

Borrower risk segmentation

Automated Power BI reporting

Machine-learning-based default prediction

👨‍💻 Author

Adapa Mohan Naga Sai Rajesh

B.Tech – Petroleum Engineering
IIT (ISM) Dhanbad

Areas of Interest:
SQL | Power BI | Data Analytics | Business Intelligence
