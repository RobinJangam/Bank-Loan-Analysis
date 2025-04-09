# Bank-Loan-Analysis (Tableau Project)

Bank Loan Report – Lending Performance Dashboard
Project Overview
As part of my data analytics journey, I developed an end-to-end Bank Loan Report designed to evaluate and monitor a financial institution’s loan performance. This project leverages key metrics, advanced filtering, and interactive visuals to provide actionable insights into lending activities. Built using tools like Tableau for visualization and SQL/Excel for data preparation, the dashboards aim to support strategic decision-making with a focus on loan quality, borrower trends, and portfolio health.
 
Objectives
The main goals of this project were to:
•	Analyze the health of the bank’s loan portfolio
•	Compare loan performance over time
•	Differentiate between good and bad loans
•	Visualize regional, financial, and demographic patterns
•	Enable data-driven decisions through dynamic dashboards
 
Dashboard 1: Loan Summary Dashboard
![image](https://github.com/user-attachments/assets/c43b9167-45ec-4e9a-a384-8032be4be13a)

This dashboard provides a high-level overview of loan-related Key Performance Indicators (KPIs) with comparisons across different time frames such as Month-to-Date (MTD) and Month-over-Month (MoM).
Key Metrics:
•	Total Loan Applications (All-Time, MTD, MoM)
•	Total Funded Amount (Disbursed Loans - All-Time, MTD, MoM)
•	Total Amount Received (Repayments from Borrowers - All-Time, MTD, MoM)
•	Average Interest Rate (Portfolio-Wide, MTD, MoM)
•	Average Debt-to-Income (DTI) Ratio (All Loans, MTD, MoM)
Good Loans vs Bad Loans:
I segmented the loan portfolio based on loan status to differentiate Good Loans and Bad Loans:
Good Loan KPIs:
•	Fully Paid or Current Loans
•	Applications Count, Funded Amount, and Received Amount
Bad Loan KPIs:
•	Charged-Off Loans
•	Applications Count, Funded Amount, and Received Amount
 
Dashboard 2: Loan Overview Dashboard
![image](https://github.com/user-attachments/assets/9dec4830-2c02-447a-9f60-7226a854b8b2)

This dashboard highlights visual trends and patterns across multiple dimensions of the loan dataset using intuitive charts and maps.
1. Monthly Trends (Line Chart)
•	Metrics: Total Applications, Funded Amount, Received Amount
•	Objective: Identify seasonal trends and portfolio growth over time
2. Regional Analysis (Filled Map)
•	Visualizes lending activity across U.S. states
•	Helps detect high-performing regions or underserved areas
3. Loan Term Analysis (Donut Chart)
•	Comparison of loan volumes and amounts by term (e.g., 36 vs. 60 months)
•	Understands borrower preferences and funding risk by term
4. Employment Length (Bar Chart)
•	Breaks down loan performance based on borrowers' job tenure
•	Assesses risk by employment stability
5. Loan Purpose Breakdown (Bar Chart)
•	Categories like debt consolidation, credit card refinance, etc.
•	Understand why borrowers are seeking loans
6. Home Ownership (Tree Map)
•	Segments loan data by home ownership status (Own, Rent, Mortgage)
•	Evaluates how housing conditions impact lending behavior
 
Dashboard 3: Detailed Loan Dashboard
![image](https://github.com/user-attachments/assets/ae8a504d-ae20-4de9-a516-cafe0ad5bea0)

The Details Dashboard serves as a comprehensive data reference panel that brings together borrower-level and loan-level insights in one consolidated view.
Key Features:
•	Loan Status Grid View
•	Filters for Loan Grade, Purpose, Term, and State
•	View metrics like Funded Amount, Received Amount, Interest Rate, and DTI per loan record
•	Designed for quick, detailed exploration of individual loans and borrower segments
 
Tools Used
•	Tableau Desktop – For dynamic dashboard creation
•	Microsoft Excel – For data cleaning and manipulation
•	PostgreSQL (PgAdmin 4) – For SQL queries and data extraction
 
Impact
This project reflects my ability to:
•	Handle end-to-end dashboard design
•	Apply business context to financial data
•	Create clean, interactive visuals
•	Deliver executive-friendly and data analyst–ready reports
