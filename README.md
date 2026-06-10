# SCHOOL-FINANCIAL-ANALYSIS-REPORT
This projesct analyzes the financial performance and sustainability of a small private school in Kenya with approximately 220 pupils. The analysis focuses on fee collection efficiency, expense management, profitability and overall financial health using Excel, SQL, Python and Power BI. 

The goal of this project was to simulate a real-world business intelligence workflow by transforming raw school financial data into actionable insights and interactive dashboards.


Data Privacy Notice: All student names and identifying information were anonymized before publication. The analysis and visualizations are based on anonymized records to protect student privacy while preserving analytical value.


## Business Problem
The school needed to understand:
Whether it is financially sustainable.

How effective fee collection is.

Which expense categories consume the most resources.

The level of outstading balances.

Overall profitability and operational efficiency.

### Tools and Technologies
Excel- Data cleaning and preparation

SQL- Database design and querying

Python- Financial analysisand calculations

Power BI- Dashboard development and visualization

Power Point- Executive presentation and reporting

## Dataset Description
The Fees Table contains student-level fee records including: Student ID, student name, tuition fees, transport fes, arrears, other fees, amount paid, outstanding balance and payment status.
The Expense table contains operational expense data including: Transaction ID, Expense description, Expense category, amount and notes.

## Data Cleaning and Preparation
The raw data was cleaned in excel by: Removing duplicates, standardizing student names, formatting data types corretly, handling missing values, structuring datasets for SQL import.
The cleaned datastes were exported as CSV files for database integration and analysis.

## SQL Database Design
A relational database was designed to organize and analyze the financial data. 

Key SQl tasks were creating tables,importing datasets, altering tables, aggregating revenue and expense data, calculating profitability metrics and analyzing fee collection performance.

## Power BI Dashboard
An interactive dashboard was created to visualize executive KPIs(total revenue, total expenses, profit, collection rate, outstanding balance and analytical visualizations(revenue vs expenses, cleared vs uncleared stuents and amounts, expense category breakdown, top fee defaulters and financial sustainability metrics).

<img width="1139" height="638" alt="image" src="https://github.com/user-attachments/assets/5158b64e-32dd-4ce2-94dd-d672c41b10e7" />


## Python Analysis
Pythton was used for: Profit calculation, cost-per-student analysis, financial ratio calculations, identifying high-risk fee defaulters and additional exploratory analysis. 
Librariees used: Pandas, NumPy and Matplotlib.

## Key Insights
1.The school is profitable, but margins are thin. 

The school generated a total collected revenue of KES 2.17M against total operational expenses of KES 1.89M, resulting in a net profit of approximately KES 282.7K.

The school achieved a profitability margin of 13.03% indicating that operations are generating a surplus aftercovering expenses. However, the margin remains relatively modest, suggesting the school is still vulnerable to delaayed fee payments, rising operational costs or drops in enrolment. 
The school is financially viable but operates with limited financial cuhion.

2.Enrolment is well above break-even point.

The break-even point(BEP) is 122 students, while current enrolment stands at 220 students. Thos means the school is operating 98 students above break-even, providing a positive safety margin.
Current enrollment levels are sufficient to sustain operations and generate profit.

3.Strong operational leverage exists

Because the school is significantly above break-even, additional students contribute disproportionately to profit since fixedcosts are already covered.
Growth in enrollment has a strong positive impact on profitability.

4. Fee Collection remains a major financial risk.

The collection rate is 71.78%, meaning nearly 28% of expected revenue remains uncollected. Outstanding balances continue to constrain cash flow despite the school being technically profitable. 
Profitability is being weakened by inefficient fee collection.

5. Salaries and wages are the largest cost driver.

The expense dashboard shows that salaries and wages rpresent the largest share of operational expenses. This is common in education institutions, but excessive payroll growth could reduce profitability over time.

6. Variable cost per student is relatively low.

The variable cost per student is aprroximately Kes 2024 compared to an average fee contribution of Kes 13,757 per student.
Each additional student contributes significantly more revenue than cost improving profitability as enrollment grows which indicates economies of scale, efficient resource utilization and strong marginal contribution per student.

7. Fixed vs Variable cost structure
The school’s cost structure is heavily weighted toward fixed costs, meaning most operational expenses remain constant regardless of student numbers.
Maintaining enrollment levels is essential because fixed costs such as salaries and rent continue even when fee collection fluctuates.

8. Revenue heavily depends on enrolment stability
Since the school's revenue model is primaily fee-based maintaining enrolment levels is critical for sustainability. Enrolment retention is directly linked to financial health.
A decline in student numbers could quickly compress profit margins.

9. High outstanding balances suggest cash flow pressure
Although the school is profitable on paper, large outstanding balances may create operational cash shortages. Profitability does not necessarily translate into healthy liquidity.
This may affect: salary payments, supplier payments and infrastructure investment.

10. The school demonstrates economies of scale
Since fixed costs are already covered after 122 students, the current enrolment of 220 allows costs to be spread more efficiently. The school benefits from from economies of scale, improving financial efficiency as enrolment increases.

11. Financial sustainability outlook is positive
The school is currently profitable, above break-even and operationally sustainable. However, long-term sustainability depends on improving fee collection, controlling salary groth and maintaining enrolment.

## Recommendation 
Improve fee collection through automated reminders, instalment tracking and digital payment integration.

Monitor salary growth by optimizing staffing efficiency and aligning hiring with enrolment growth.

Strengthen cash-flow monitoring through monthly financial dashboards, liquidity tracking and arrears reporting.
