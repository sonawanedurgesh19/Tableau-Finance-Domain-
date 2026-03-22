1. Project Title - Bank Loan Performance Analysis & Risk Monitoring System 

2. Short Description:
This project involves the creation of a comprehensive Tableau-based reporting system designed to monitor and analyze bank lending operations. It tracks $435.8M in total funded loans and assesses the health of the portfolio by classifying loans into "Good" and "Bad" categories based on repayment status.

3. Problem Statement:
The organization lacked a consolidated, real-time view of its lending activities, making it difficult to:
Monitor key performance indicators (KPIs) like total applications, funded amounts, and cash flow.
Assess borrower financial health through Debt-to-Income (DTI) ratios and interest rate trends.
Identify regional disparities and seasonal trends in loan disbursement.
Distinguish between profitable "Good Loans" and risky "Bad Loans" (Charged Off) to make data-driven decisions.

4. Goal of Dashboard:
The primary goal is to provide a one-stop solution for users to access critical loan data. The dashboard aims to:
Visualize monthly and regional trends.
Analyze the impact of borrower attributes (employment length, home ownership) on lending.
Enable granular drill-downs into individual loan details for efficient portfolio management.

5. Walkthrough of Key Visuals:
The system is divided into three specialized views:
Summary Dashboard: Features high-level KPIs for Total Applications (38.6K), Funded Amount ($435.8M), and Amount Received ($473.1M). It includes a "Loan Status Grid View" for performance categorization.

Overview Dashboard:
Line Chart: Displays monthly trends to identify seasonality.
Filled Map: Shows regional lending activity by state.
Donut Chart: Breaks down loan distribution by term length (36 vs. 60 months).
Bar Charts: Analyze lending metrics by employment length and loan purpose.
Tree Map: Displays the impact of home ownership (Mortgage vs. Rent).

3. Details Dashboard: Provides a comprehensive grid with consolidated borrower profiles, including loan IDs, issue
   dates, interest rates, and purposes.


6. Business Impacts:
Improved Risk Assessment: By identifying that 13.8% of loans are "Bad" (Charged Off), the bank can refine its credit-scoring models.
Enhanced Cash Flow Monitoring: Tracking the Month-over-Month (MoM) change in amounts received (15.8% increase) helps in liquidity planning.
Targeted Marketing: Analyzing loan purposes (e.g., Debt Consolidation being the primary driver) allows for tailored financial products.

7. Tools & Methodology:
Tool Used: Tableau.
Process:
Data Aggregation: Calculating total metrics and MTD/MoM growth rates to provide temporal context.
Logic Implementation: Creating "Good Loan" vs. "Bad Loan" KPIs based on specific "Loan Status" criteria.
Visual Design: Utilizing a variety of charts (Line, Map, Donut, Bar, Tree Map) to represent different dimensions of the data (Time, Geography, Category).

8. Key Insights
Portfolio Health: 86.2% of loans are classified as "Good Loans".
Primary Drivers: Debt consolidation is the most frequent reason for borrowing, accounting for $253.8M in received payments.
Borrower Profile: Borrowers with 10+ years of employment represent the largest share of repayments ($125.9M).
Regional Dominance: States like California (CA) and Texas (TX) show significantly higher lending activity on the regional map.
Loan Terms: The majority of the total amount received (62.3%) comes from 36-month loan terms.
