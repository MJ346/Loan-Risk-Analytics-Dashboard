# Loan-Risk-Analytics-Dashboard


## Project Overview
This project contains **interactive Power BI dashboards** designed to analyze loan defaults, applicant profiles, and financial risk metrics. The dashboards leverage **Dataflows, DAX, and Power Query** to clean, transform, and visualize large datasets (2 lakh+ rows).

---

🔹 Key Insights from the Dashboard
1. Loan Default & Overview

Loan Purpose: Home loans account for the highest loan amount, but "Other" purposes have the lowest.

Employment Type & Default Risk:

Unemployed borrowers have the highest default rate (3.19%).

Full-time employees have the lowest default rate (2.36%), highlighting employment stability as a strong risk mitigator.

Age Group: Adults and middle-aged borrowers take the largest average loan amounts, while teens borrow significantly less.

Yearly Trend: Default rates peaked in 2016 (11.75%) before stabilizing by 2018 (11.6%).

2. Applicant Demographics & Financial Profile

Credit Score: Surprisingly, borrowers with higher credit scores take lower median loan amounts compared to low scorers.

Marital Status & Age: Single and married borrowers in the adult/middle-age groups take the highest average loan amounts (128K+).

Dependents: Presence of dependents does not significantly affect loan amount among middle-aged borrowers.

Education: Bachelor’s degree holders account for the largest share of loans, while PhD holders account for the least.

3. Financial Risk Metrics

YOY Loan Growth:

Loan amounts grew the most in 2015 (+1.3M) and 2018 (+1.7M).

Sharp decline in 2014 (-1.53M) and 2017 (-1.08M) indicates cyclical lending patterns.

YOY Default Rate: Defaults rose sharply in 2015, dipped in 2017 (-2.83%), then spiked again in 2018 (+1.88%).

Income Bracket:

High-income borrowers account for ~21.7B loans, far exceeding medium (7.2B) and low-income (6.3B).

Loan distribution is fairly equal across employment types within the high-income bracket.

4. Loan Repayment & Risk Analysis

Loan Term: Default rate remains stable (~11.6%) across 20–60 month loan terms → tenure does not majorly influence default risk.

Loan Purpose Risk: Business loans have the highest default rate (12.3%), while home loans have the lowest (10.2%).

Debt-to-Income Ratio (DTI): Higher DTI is positively correlated with higher default probability.

Credit Score & Risk Matrix:

Borrowers with very low credit scores face the highest default risk (16.56%), regardless of loan size.

Even in the high credit score group, smaller loans (<50k) show higher relative default risk compared to medium/large loans.

---

## Technologies & Skills Used
- **Power BI Desktop**: Dashboard creation and visualization  
- **Dataflows**: Centralized data preparation and automated refresh  
- **DAX**: Calculated measures and KPIs  
- **Power Query**: Data cleaning and transformation  

---## Project Demo
You can explore the interactive Power BI dashboards here:  
[Open Power BI Report](https://app.powerbi.com/groups/me/reports/296439f0-554d-4218-84d1-ee37b5e97438/b944ca83982eacb3819e?experience=power-bi)



