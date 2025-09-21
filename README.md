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

Exploratory Data Analysis (EDA) – Identified patterns, outliers, and risk segments

Power BI Dashboards – Built dashboards for:

Loan Analysis (Risk & Portfolio Distribution)

Deposit Analysis (Behavior & Preferences)

Executive Summary (KPIs & Strategy Insights)

📊 Key Insights

Total Clients: 194

Total Loans: $304.40M

Total Deposits: $248.28M

High dependency on Business Lending clients

Gender and joining year filters reveal customer retention trends

📁 Repository Contents

sql/ → SQL scripts (table creation, queries)

notebooks/ → Python notebooks for data cleaning & EDA

powerbi/ → Power BI dashboard file (.pbix)

docs/ → Project report (PDF) + dashboard screenshots

🔹 Insights from Dashboard
📊 Banking Dashboard (Overview)

Client Base: 194 total clients → a relatively small but well-segmented customer pool.

Deposits vs Loans:

Loans: $304.40M

Deposits: $248.28M
👉 The bank has higher loan exposure than deposits, which could be risky if defaults rise.

Business Lending: A large share of loans are from business clients → concentration risk, but also indicates a strategic focus on businesses.

Filters (Gender & Joining Year): Allow slicing → reveal trends in which segments are more profitable or risk-heavy.

📊 Loan Analysis Dashboard

Risk Categories: Loans segmented by risk profile show how much exposure the bank has in high vs. low risk clients.

Demographics: Loan defaults / repayments differ by gender, age, or occupation.

Portfolio Distribution: Shows where (location) and when (time period) loans were disbursed → helps in tracking seasonal loan trends or regional concentration.

📊 Deposit Analysis Dashboard

Deposit Breakdown: Checking vs. Savings deposits distribution → provides insight into client saving behavior.

Customer Segments: Different client groups (business, individuals, genders) show different deposit behaviors.

Deposits are lower than loans, which may pressure liquidity if not managed properly.

📊 Executive Summary Dashboard

High-level KPIs (Clients, Loans, Deposits) give a snapshot for leadership.

Highlights performance vs. targets (though targets weren’t shown in PDF, can be added).

Pinpoints opportunities for growth (e.g., increase deposits, diversify loan portfolio).

🔹 Key Takeaways (Your Insights)

Loans > Deposits → Bank is lending more than it holds in deposits → indicates growth strategy but adds risk.

Business Lending Dominates → High dependency on businesses; diversify into retail to reduce concentration risk.

Risk Profiles → Identifying risky borrowers is crucial; predictive analytics can reduce NPA (non-performing assets).

Engagement Trends → Client joining year trends + gender filters reveal who stays longer, who deposits more.

Opportunities → Focus on increasing deposits, targeting underrepresented segments, and improving repayment prediction models.
