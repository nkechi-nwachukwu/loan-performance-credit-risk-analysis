# 📊 Loan Performance & Credit Risk Analysis

### End-to-End Credit Risk & Portfolio Analytics Project

An end-to-end data analytics project analyzing loan performance, borrower behavior, credit risk, default patterns, and portfolio profitability.

The project combines **SQL and Excel** to transform raw lending data into actionable insights around borrower risk, loan exposure, repayment performance, and portfolio returns.

---

## 📌 Project Overview

Financial institutions need to balance loan growth with portfolio quality and profitability. Rapid lending growth can increase exposure to defaults, while poor risk segmentation can result in lending decisions that generate insufficient returns.

This project analyzes historical loan data to understand:

* Overall loan portfolio performance
* Borrower risk characteristics
* Default patterns
* Loan exposure by status
* Credit grade performance
* Loan profitability
* Risk versus return across borrower segments
* Factors associated with loan default and repayment behavior

The analysis demonstrates how **SQL and Excel-based reporting** can be used to monitor credit portfolios and support data-informed lending decisions.

---

## Dashboard Overview
<img width="1800" height="1200" alt="Loan Performance Mockup " src="https://github.com/user-attachments/assets/7be67bd7-ebfb-469a-9798-b2c5d9cb5934" />

---

## 🎯 Business Problem

The lending portfolio showed significant growth in loan disbursements, but increasing defaults and negative returns created concerns around portfolio risk and profitability.

The key business questions were:

* How is the overall loan portfolio performing?
* Which borrower segments present higher credit risk?
* Which credit grades have the highest default rates?
* How does loan size affect portfolio exposure?
* What relationship exists between interest rates and default?
* Which loan purposes generate the strongest or weakest returns?
* How does portfolio growth affect overall risk?
* Which borrower and loan characteristics should receive closer monitoring?

---

## 🎯 Project Objectives

The analysis aims to:

1. Analyze overall loan portfolio performance.
2. Identify default patterns and high-risk borrower segments.
3. Evaluate factors influencing loan repayment behavior.
4. Segment borrowers based on credit risk characteristics.
5. Analyze loan profitability and portfolio returns.
6. Compare risk versus return across loan segments.
7. Build reporting views that support credit risk monitoring.
8. Generate data-driven recommendations for improving portfolio quality.

---

## 📂 Dataset

**Dataset:** Lending Club Loan Dataset

**Records:** 10,000+ loan records

The dataset contains borrower, financial, and loan-level information used to analyze credit risk and portfolio performance.

### Key Fields

* Loan Amount
* Borrower Income
* Credit Grade
* Loan Purpose
* Interest Rate
* Loan Term
* Debt-to-Income Ratio
* Loan Status
* Default Status
* Geographic Information
* Repayment Information
* Financial Performance Metrics

The dataset provides sufficient information to evaluate both **borrower risk** and **loan-level financial performance**.

---

## 🛠 Tools & Technologies

### SQL

* Data transformation
* Data cleaning
* Aggregations
* Filtering and segmentation
* Risk analysis
* Portfolio analysis
* KPI calculations
* Profitability analysis

### Microsoft Excel

* Power Query
* Power Pivot
* Data modeling
* Calculated measures
* PivotTables
* Interactive dashboards
* Data visualization

---

## 🔄 Analysis Workflow

```text
Raw Lending Data
       ↓
Data Cleaning & Transformation
       ↓
SQL Analysis & Data Preparation
       ↓
Risk & Borrower Segmentation
       ↓
Loan Performance Analysis
       ↓
Profitability Analysis
       ↓
Excel Data Model
       ↓
Interactive Reporting Dashboard
       ↓
Business Insights & Recommendations
```

---

# 🧹 1. Data Preparation

The raw lending data was prepared for analysis by:

* Handling missing values
* Correcting inconsistent formats
* Standardizing financial fields
* Reviewing duplicate records
* Preparing categorical variables
* Structuring loan and borrower attributes for analysis
* Creating calculated risk and profitability metrics

The cleaned dataset was then used for SQL analysis and Excel reporting.

---

# 🔍 2. Exploratory Data Analysis

Exploratory analysis was conducted to understand:

* Loan distribution
* Borrower characteristics
* Credit grade distribution
* Loan purpose distribution
* Default patterns
* Loan status
* Interest rate distribution
* Loan exposure
* Portfolio growth
* Profitability across segments

---

# 🧮 3. Risk-Based Analysis

Additional analytical features were developed to support borrower risk assessment.

### Risk dimensions included:

* Credit grade
* Income level
* Debt-to-income ratio
* Loan amount
* Interest rate
* Loan term
* Loan purpose
* Geographic distribution
* Loan status

Borrowers were segmented across these dimensions to identify patterns associated with higher portfolio risk.

---

# 📊 4. Key Analysis Areas

## Loan Portfolio Performance

The analysis evaluated:

* Total loan disbursements
* Loan volume
* Portfolio growth
* Loan status
* Repayment performance
* Default rate
* Portfolio exposure

This provided an overall view of portfolio health and lending activity.

---

## Default Rate Analysis

Default rates were analyzed across:

* Credit grades
* Interest rates
* Loan purposes
* Income levels
* Loan terms
* Geographic segments

This helped identify borrower groups associated with higher observed default rates within the dataset.

---

## Credit Grade Analysis

Credit grades were compared to evaluate differences in:

* Default rates
* Loan exposure
* Interest rates
* Net returns
* Portfolio contribution

The analysis identified **D-grade borrowers as the highest-default segment in the analyzed portfolio, at approximately 14%**.

---

## Loan Exposure by Status

Loan exposure was analyzed across different loan statuses to understand how much of the portfolio was associated with:

* Current loans
* Completed loans
* Charged-off/defaulted loans
* Other loan statuses

This helps distinguish portfolio growth from actual portfolio quality.

---

## Interest Rate vs Default Rate

The relationship between interest rates and default rates was analyzed to understand whether higher-priced loans were associated with greater observed credit risk.

This analysis provides a basis for evaluating whether loan pricing appropriately reflects observed risk.

---

## Loan Profitability

Loan profitability was analyzed across:

* Credit grades
* Loan purposes
* Borrower segments
* Loan types

The analysis compared loan returns against losses and exposure to identify segments with stronger or weaker financial performance.

---

## Loan Purpose Analysis

Loan performance was compared across different purposes to identify segments contributing disproportionately to portfolio gains or losses.

**Debt consolidation loans generated the largest observed losses in the analyzed portfolio, at approximately $77M.**

---

# 📈 Key KPIs

| KPI                     | Purpose                                            |
| ----------------------- | -------------------------------------------------- |
| Total Loan Amount       | Measures total lending exposure                    |
| Total Loan Count        | Measures portfolio volume                          |
| Default Rate            | Measures observed credit risk                      |
| Average Interest Rate   | Measures loan pricing                              |
| Average Loan Amount     | Measures typical loan exposure                     |
| Net Returns             | Measures portfolio profitability                   |
| Total Loss              | Measures financial impact of poor-performing loans |
| Loan Growth             | Tracks portfolio expansion                         |
| Loan Exposure by Status | Measures portfolio composition                     |
| Risk by Credit Grade    | Compares borrower risk levels                      |

---

# 💡 Key Insights

### 1. Portfolio growth increased risk exposure

Loan disbursements grew significantly, reaching approximately **$163M** in the analyzed portfolio.

The growth in lending activity also increased the amount of capital exposed to potential credit losses.

### 2. Default risk varied significantly by credit grade

D-grade borrowers recorded the highest observed default rate at approximately **14%**, making this segment an important risk-monitoring group within the analyzed portfolio.

### 3. Portfolio profitability was negative

The analysis identified approximately **-$138M in net losses**, indicating that loan growth did not translate into positive portfolio returns within the modeled analysis.

### 4. Debt consolidation was a major source of losses

Debt consolidation loans accounted for approximately **$77M in observed losses**, making the segment an important contributor to overall portfolio losses.

### 5. Risk and return were not evenly distributed

Different credit grades and loan purposes produced substantially different risk and return profiles.

This highlights the importance of evaluating both **credit risk and profitability** rather than focusing only on loan growth.

---

# 💼 Business Recommendations

Based on the analysis, the following actions were identified for consideration:

### 1. Strengthen risk-based lending

Use borrower risk characteristics and observed portfolio performance to support differentiated lending and pricing strategies.

### 2. Closely monitor higher-risk credit segments

Segments with consistently higher observed default rates should receive enhanced monitoring and underwriting review.

### 3. Review high-loss loan purposes

Loan categories contributing disproportionately to portfolio losses should be reviewed to understand whether underwriting, pricing, borrower characteristics, or recovery processes are driving the losses.

### 4. Improve loan recovery

Strengthen post-default recovery processes through structured repayment arrangements, proactive collections, and appropriate recovery strategies.

### 5. Balance growth with portfolio quality

Rapid loan growth should be evaluated alongside default rates, loss exposure, and profitability to ensure that portfolio expansion remains sustainable.

### 6. Use risk-based pricing

Interest rates and lending terms can be evaluated against observed borrower risk to better align expected returns with portfolio exposure.

---

# 📊 Dashboard

The Excel dashboard provides a consolidated view of:

* Portfolio performance
* Loan exposure
* Default risk
* Borrower profiles
* Credit grade performance
* Loan profitability
* Loan status
* Risk trends

### Dashboard Preview

<img width="1161" height="654" alt="credit risk dashboard" src="https://github.com/user-attachments/assets/8b89f63e-02a0-42b1-b1e2-642a322c4157" />


---

## 📷 Dashboard Screenshots

### Portfolio Health Dashboard

<img width="1141" height="638" alt="porfolio health dashboard" src="https://github.com/user-attachments/assets/986bd2c9-7565-4678-a7e1-99e490c9cdf8" />

### Default Rate vs Interest Rate

<img width="303" height="224" alt="interest rate" src="https://github.com/user-attachments/assets/105b1675-d067-42ea-9443-d89f52d95d8c" />
### Loan Exposure by Status

<img width="297" height="359" alt="loan exposure" src="https://github.com/user-attachments/assets/350c5d77-e0d7-4aed-9fd6-e0302e14fe81" />
### Net Returns by Loan Grade

<img width="274" height="357" alt="net returns" src="https://github.com/user-attachments/assets/b0cfcd43-911b-46fb-901a-3694fb4283ad" />
### Portfolio KPIs

<img width="189" height="517" alt="kpi" src="https://github.com/user-attachments/assets/f0eb224b-adef-4f61-9b33-5f1a07f15cac" />
### Borrower Profile

<img width="529" height="499" alt="borrowers profile" src="https://github.com/user-attachments/assets/a393074a-54ec-4e9d-b4b2-f36cab00748a" />
---

# 📁 Repository Structure

```text
loan-performance-credit-risk-analysis/
│
├── README.md
│
├── data/
│   └── README.md
│
├── sql/
│   ├── 01_data_cleaning.sql
│   ├── 02_loan_portfolio_analysis.sql
│   ├── 03_credit_risk_analysis.sql
│   ├── 04_borrower_segmentation.sql
│   └── 05_profitability_analysis.sql
│
├── excel/
│   └── Loan_Performance_Credit_Risk_Analysis.xlsx
│
├── images/
│   ├── dashboard-overview.png
│   ├── default-rate-vs-interest-rate.png
│   ├── loan-exposure-by-status.png
│   ├── net-returns-by-loan-grade.png
│   ├── kpis.png
│   ├── borrower-profile.png
│   └── portfolio-health-dashboard.png
│
└── documentation/
    └── analysis-notes.md
```

---

# 📂 Data Availability

The original Lending Club dataset is not included in this repository.

The analysis uses a Lending Club dataset containing 10,000+ loan records.

For reproducibility, users should obtain the appropriate dataset from its original source and place the required data files inside the `data/` directory.

> **Note:** Dataset availability and licensing may vary depending on the source used.

---

# 📊 Excel Workflow

The complete Excel workflow includes:

* Data preparation with Power Query
* Data modeling with Power Pivot
* Calculated metrics
* Portfolio analysis
* Borrower segmentation
* Credit risk analysis
* Profitability analysis
* Interactive reporting

**🔗 [Explore the Full Excel Workflow]**
https://1drv.ms/x/c/6c87140a9abfc95f/IQCAQPOdxX7mRqtwOZ1M79fXAf4dhiR0gGe_4xHG48pLnmQ?e=iF40NT
---

# 🚀 Business Outcome

The project demonstrates how lending data can be transformed into a structured **credit risk and portfolio reporting solution**.

The analysis moves beyond measuring loan growth by combining:

**Portfolio Growth + Credit Risk + Loan Exposure + Default Behavior + Profitability**

to provide a more complete view of lending performance.

The overall analytical direction is:

> **High-growth lending → Risk-controlled and profitability-focused portfolio management**

---

# 🧠 Skills Demonstrated

* Credit Risk Analytics
* Loan Portfolio Analysis
* Financial Data Analysis
* SQL
* Microsoft Excel
* Power Query
* Power Pivot
* Data Cleaning
* Data Transformation
* Data Modeling
* KPI Development
* Borrower Segmentation
* Risk Analysis
* Profitability Analysis
* Dashboard Development
* Business Intelligence
* Data Storytelling
* Business Recommendations

---

# 🔗 Project Links

### 🌐 Portfolio Project

[View Loan Performance & Credit Risk Analysis](https://sites.google.com/view/dorothysdatadesk/projects/loan-performance-credit-risk-analysis)

### 📊 Excel Analysis
https://1drv.ms/x/c/6c87140a9abfc95f/IQCAQPOdxX7mRqtwOZ1M79fXAf4dhiR0gGe_4xHG48pLnmQ?e=iF40NT

---

# 👩🏽‍💻 Author

**Nkechi Nwachukwu**

**Data Analyst | Reporting & Business Intelligence**

Focused on transforming raw data into clear reports, dashboards, and actionable business insights using **SQL, Power BI, Excel, Tableau, and AI tools**.

Portfolio: https://dorothy-data-portfolio.lovable.app

GitHub: https://github.com/nkechi-nwachukwu

LinkedIn: https://linkedin.com/in/nkechi-nwachukwu-82ba911bb

---

⭐ If you found this project useful, feel free to explore the repository and connect with me.
