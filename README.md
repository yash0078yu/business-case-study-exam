============================================================
PROJECT TITLE: CUSTOMER CHURN ANALYSIS AND DASHBOARD
============================================================

PRODUCT OVERVIEW:
This project analyzes customer churn data using SQL for deep data 
insights and Power BI for creating an interactive visual dashboard.

------------------------------------------------------------
1. FILES INCLUDED IN THIS PROJECT:
------------------------------------------------------------
* README.txt           - Project documentation and overview.
* CustomerSubscriptions.csv - The generated dummy dataset containing 
                         customer profiles, usage, and churn status.
* ChurnAnalysis.sql    - SQL queries answering core business questions.
* ChurnDashboard.pbix  - Power BI Desktop file with interactive charts.
* ChurnSummary.txt     - Key business insights and summary findings.

------------------------------------------------------------
2. DATASET COLUMNS USED:
------------------------------------------------------------
* CustomerID       - Unique identifier for each customer
* Name             - Customer name
* Age              - Customer age
* Gender           - Customer gender
* SubscriptionType - Monthly, Quarterly, or Yearly
* SubscriptionDate - Date of subscription start
* LastLoginDate    - Last active login date
* TotalSessions    - Total usage sessions
* FeedbackScore    - Customer feedback (1 to 10)
* IsChurned        - Churn status (1 = Churned, 0 = Active)

------------------------------------------------------------
3. DASHBOARD COMPONENTS BUILT (Power BI):
------------------------------------------------------------
* KPI Cards        - Total Customers, % Churned, Avg Feedback, Avg Sessions.
* Donut Chart      - Distribution of Active vs Churned customers.
* Bar Chart        - Churn rate based on Subscription Type.
* Line Chart       - Customer onboarding trend over time.
* Scatter Plot     - Correlation between Total Sessions and Feedback Score.

------------------------------------------------------------
4. HOW TO RUN THE PROJECT:
------------------------------------------------------------
1. Import 'CustomerSubscriptions.csv' into your database to run 'ChurnAnalysis.sql'.
2. Open 'ChurnDashboard.pbix' in Power BI Desktop to interact with the visualizations.
============================================================
