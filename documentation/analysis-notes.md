# 📊 Loan Performance & Credit Risk Analysis — Analysis Notes

## 1. Project Purpose

This project evaluates loan portfolio performance, borrower risk, default behavior, loan exposure, and profitability using a Lending Club loan dataset.

The analysis combines SQL and Excel to create a structured credit risk reporting workflow.

---

## 2. Business Questions

The analysis was designed to answer the following questions:

1. How is the loan portfolio performing?
2. What proportion of loans are in default?
3. Which credit grades have the highest observed default rates?
4. Which borrower segments present greater observed risk?
5. Which loan purposes contribute the most exposure?
6. How does interest rate relate to observed default?
7. Which segments generate stronger or weaker returns?
8. How can lending growth be evaluated alongside portfolio quality?

---

## 3. Data Preparation

The raw dataset was prepared through:

* Missing-value review
* Duplicate review
* Data-type standardization
* Financial-field validation
* Categorical field standardization
* Loan status classification
* Risk segmentation

---

## 4. Analytical Framework

The project evaluates portfolio performance across four major dimensions:

### Portfolio

* Loan volume
* Total exposure
* Loan status
* Portfolio growth

### Credit Risk

* Default rate
* Credit grade
* Interest rate
* Debt-to-income ratio
* Borrower income

### Borrower Segmentation

* Income segments
* Credit grade
* Loan purpose
* DTI segments
* Geographic distribution

### Profitability

* Loan returns
* Loss exposure
* Net returns
* Risk versus return

---

## 5. Key Findings

The analysis identified several important patterns within the analyzed dataset:

* Loan disbursements reached approximately $163M.
* Overall portfolio losses were approximately $138M.
* D-grade borrowers recorded the highest observed default rate at approximately 14%.
* Debt consolidation loans contributed approximately $77M in observed losses.
* Higher-risk segments require closer monitoring when evaluating portfolio exposure.
* Portfolio growth should be evaluated alongside credit quality and profitability.

---

## 6. Dashboard

The Excel dashboard was designed to provide a consolidated view of:

* Portfolio KPIs
* Loan exposure
* Default performance
* Borrower characteristics
* Credit grade performance
* Loan profitability
* Loan status

---

## 7. Business Interpretation

The analysis suggests that loan growth alone does not provide a complete picture of lending performance.

A more comprehensive assessment should consider:

**Growth + Exposure + Default Risk + Recovery + Profitability**

This framework helps identify whether portfolio expansion is being accompanied by sustainable financial performance.

---

## 8. Recommendations

Based on the observed portfolio patterns:

* Strengthen monitoring of higher-risk borrower segments.
* Evaluate risk-based pricing approaches.
* Review loan purposes associated with disproportionate losses.
* Improve recovery and collections processes.
* Balance lending growth with portfolio quality.
* Monitor credit-grade performance regularly.

These recommendations are based on patterns observed in the analyzed dataset and should be validated against current underwriting policies, economic conditions, and additional risk data before implementation.

---

## 9. Limitations

This project is based on historical lending data and therefore has several limitations.

* Historical patterns may not represent current borrower behavior.
* Observed correlations do not necessarily establish causation.
* The dataset may not contain every variable used in real-world credit decisions.
* Portfolio profitability calculations depend on the financial fields available in the dataset.
* Risk thresholds should be validated using additional data and appropriate credit-risk methodologies.

The analysis is intended as a portfolio analytics and reporting project rather than a production credit-scoring model.
