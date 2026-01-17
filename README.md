# Customer Analytics with Python

## Live Analytics Report
👉 https://michaeljvargas.github.io/Customer-Analytics-Python/customer_analysis.html


---

## Overview
This project demonstrates an end-to-end customer analytics workflow using Python to support business decision-making. The analysis focuses on understanding revenue trends, identifying high-value customers, and flagging customers at risk of churn based on transaction behavior.

The goal of this project is to simulate how a business or risk analyst would analyze customer transaction data to provide actionable insights to stakeholders without requiring them to run code locally.

---

## Business Questions Addressed
This project answers the following key questions:

- How is revenue trending over time?
- Which customers generate the most total spend?
- What proportion of customers are repeat buyers versus one-time buyers?
- Which customers may be at risk of churn based on inactivity?

---

## Dataset
The dataset consists of simulated customer transaction data designed to reflect real-world retail or fintech use cases.

**Fields included:**
- `transaction_id` – Unique transaction identifier  
- `customer_id` – Unique customer identifier  
- `transaction_date` – Date of transaction  
- `amount` – Transaction amount  
- `category` – Product or purchase category  

The dataset structure mirrors common transaction-level data used in analytics, fraud, and risk analysis roles.

---

## Key Analyses and Insights

### Revenue Trend Analysis
- Monthly revenue is aggregated to identify trends and seasonality.
- This view helps stakeholders assess growth patterns and identify potential revenue risks early.

### Customer Value Analysis
- Total spend per customer is calculated to identify high-value customers.
- Results show that a small subset of customers contributes a disproportionate share of total revenue, a common real-world pattern.

### Repeat vs One-Time Customers
- Customers are classified based on purchase frequency.
- This analysis highlights retention opportunities and informs customer engagement strategies.

### Churn Risk Identification
- Customers with no activity in the last 90 days are flagged as at-risk.
- This approach mirrors how analytics teams support marketing, retention, or fraud-prevention initiatives.

---

## Tools and Technologies
- Python  
- pandas  
- matplotlib  
- Jupyter Notebook  
- GitHub Pages (for publishing a live report)

---

## Project Structure
Customer-Analytics-Python/
│
├── data/
│ └── transactions.csv
│
├── notebooks/
│ └── customer_analysis.ipynb
│
├── docs/
│ └── index.html # Live analytics report
│
├── requirements.txt
└── README.md


---

## How to Run Locally
1. Clone the repository:


git clone https://github.com/michaeljvargas/Customer-Analytics-Python.git


2. Install dependencies:


pip install -r requirements.txt


3. Open the notebook:


notebooks/customer_analysis.ipynb


4. Run all cells to reproduce the analysis.

---

## Why This Project Matters
This project highlights the ability to:
- Translate raw data into business insights
- Communicate analytical findings clearly
- Balance technical execution with business context
- Deliver results in a stakeholder-friendly format

It reflects real-world expectations for roles in business analytics, risk analysis, fraud analytics, and fintech.

---

## Future Enhancements
- Expand the dataset to include longer time horizons
- Add customer segmentation or cohort analysis
- Build an interactive dashboard using Streamlit
- Integrate forecasting or anomaly detection models

---

## Author
Michael Vargas  
Business Analytics | Risk | FinTech | Python

