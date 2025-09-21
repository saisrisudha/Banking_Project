# Banking_Project
This project demonstrates end-to-end data analytics skills using SQL, Python, and Power BI. The goal was to analyze banking and financial data to assess risks, improve loan approval decisions, and generate actionable business insights.

🛠️ Tools & Skills Demonstrated

SQL – Data extraction, joins, transformations, relational schema design

Python (EDA) – Data cleaning, exploratory data analysis, visualizations (pandas, matplotlib, seaborn)

Power BI – Interactive dashboards with DAX functions (SUMX, DISTINCTCOUNT, SWITCH, DATEDIFF)

Data Storytelling – Final presentation of insights in PPT/PDF

📂 Project Workflow

Data Acquisition – Kaggle banking dataset with customer, loan, and deposit details

Database Setup – Imported into MySQL, applied primary/foreign key relationships

Exploratory Data Analysis (EDA) – Identified patterns, outliers, and risk segments using Python

Power BI Dashboards – Built dashboards for:

Loan Analysis (Risk & Portfolio Distribution)

Deposit Analysis (Behavior & Preferences)

Executive Summary (KPIs & Strategy Insights)

📊 Key Insights (KPIs)

Total Clients: 194

Total Loans: $304.40M

Total Deposits: $248.28M

High dependency on Business Lending clients

Gender and Joining Year filters reveal customer retention trends

📁 Repository Contents
sql/        → SQL scripts (table creation, queries)  
notebooks/  → Python notebooks for data cleaning & EDA  
powerbi/    → Power BI dashboard file (.pbix)  
docs/       → Project report (PDF) + dashboard screenshots  

🔹 Dashboard Insights
📊 Banking Dashboard (Overview)

Client Base: 194 total clients → relatively small but well-segmented customer pool.

Deposits vs Loans:

Loans: $304.40M

Deposits: $248.28M
👉 Higher loan exposure than deposits → risky if defaults rise.

Business Lending: Majority of loans from business clients → concentration risk but shows strategic focus.

Filters (Gender & Joining Year): Useful for identifying profitable or risk-heavy segments.

📊 Loan Analysis Dashboard

Risk Categories: Segmentation by borrower risk highlights exposure across profiles.

Demographics: Loan repayment/default trends differ by gender, occupation, or income.

Portfolio Distribution: Shows where (location) and when (time) loans were disbursed → useful for tracking seasonal/regional patterns.

📊 Deposit Analysis Dashboard

Deposit Breakdown: Checking vs. Savings deposits highlight customer preferences.

Customer Segments: Behavior varies between business vs. individual clients.

Liquidity Risk: Deposits are lower than loans, which could stress liquidity if not managed well.

📊 Executive Summary Dashboard

Provides high-level KPIs (Clients, Loans, Deposits) for leadership.

Highlights performance vs. targets (future improvement: add target KPIs).

Identifies opportunities to grow deposits and diversify loan portfolios.

🔹 Key Takeaways

Loans > Deposits → Indicates growth strategy but higher financial risk.

Business Lending Dominates → Diversification into retail can reduce dependency on businesses.

Risk Profiles → Identifying risky borrowers is crucial; predictive analytics can lower NPAs.

Engagement Trends → Joining year + gender filters reveal long-term retention behaviors.

Opportunities → Grow deposits, expand into new customer segments, improve loan approval models.
