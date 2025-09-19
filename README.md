# Loan-Default
LOAN RISK ANALYSIS & FINANCIAL METRICS DASHBOARD USING POWER BI
This project demonstrates the use of Power BI and SQL Server to analyze financial loan data. The goal is to evaluate loan distribution, default risks, income patterns, and employment impact using advanced DAX measures, interactive visuals, and automated dataflows.
The dashboard helps financial institutions and analysts monitor loan performance, borrower profiles, and risk metrics in real time, assisting in data-driven decision-making.

TECH STACK
SQL Server – for importing and storing raw loan data

Power BI Service – for creating dataflows

Power BI Desktop – for data modeling and visualization

DAX (Data Analysis Expressions) – for creating custom measures (SUMX, CALCULATE, AVERAGEX, MEDIANX, FILTER, DIVIDE, etc.)

Power Query Editor – for data transformation and profiling


DATA SOURCE
The dataset contains loan records with borrower demographics, income, credit score, marital status, employment type, and repayment details.
Data was connected from SQL Server → transformed via Power BI Dataflows → consumed in Power BI Desktop for analysis.

FEATURES/HIGHLIGHTS
✔ Importing data from SQL Server into Power BI Dataflows
✔ Building interactive dashboards with KPIs & charts
✔ DAX measures for:<img width="1329" height="729" alt="Screenshot 2025-09-18 224901" src="https://github.com/user-attachments/assets/c8502f98-7430-4377-bde4-6a3959b1db64" />
<img width="1319" height="729" alt="Screenshot 2025-09-18 224840" src="https://github.com/user-attachments/assets/0f779beb-a8be-4bba-9472-f7d18a5626d6" />
<img width="1319" height="736" alt="Screenshot 2025-09-18 224821" src="https://github.com/user-attachments/assets/498d858f-e690-4436-9d76-c202f9459349" />

Median Loan Amount by Credit Score
✔ Data Validation using multiple charts (Column, Donut, Decomposition Tree)
✔ Schedule refresh setup for real-time updates


GOALS
To design a comprehensive loan risk analysis system that highlights:
Loan trends over time (YOY & YTD)
Borrower segmentation (age, employment, credit score, marital status)
Loan default patterns and risk factors
Data-driven insights for financial risk management


KEY VISUALS
The dashboard provides an end-to-end view of loan performance & risks with:
YOY Loan Amount & Default Change (trend line charts)
YTD Loan Amount by Credit Score & Marital Status (flow diagram)
Loan Breakdown by Income Bracket & Employment Type (Sankey-style chart)

BUSINESS IMPACT 
Identified high-risk borrower groups by analyzing defaults across employment and marital categories
Detected income-based loan distribution, showing higher loans concentrated in high-income full-time employees
Measured credit score influence on loan approvals & defaults
Year-over-year comparison revealed loan growth but fluctuating default patterns, highlighting areas for risk intervention
Supports strategic lending decisions and portfolio risk management
















