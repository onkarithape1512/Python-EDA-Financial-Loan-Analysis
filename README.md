# 📊 End-to-End Loan Portfolio Analysis  
## Exploratory Data Analysis (EDA) Using Python

---

## 🚀 Project Summary

This project presents a comprehensive **Exploratory Data Analysis (EDA)** of a financial loan dataset to evaluate lending performance, borrower behavior, and portfolio health.

The analysis transforms raw loan-level data into structured business insights using Python. It focuses on:

- Portfolio performance measurement  
- Good vs Bad loan classification  
- Risk assessment metrics  
- Regional and behavioral trend analysis  
- KPI-driven decision support  

This project simulates a real-world financial analytics use case similar to banking and NBFC credit risk monitoring.

---

# 🎯 Business Problem

Financial institutions must continuously monitor:

- Loan disbursement trends  
- Repayment performance  
- Risk exposure  
- Borrower financial stability  
- Regional lending distribution  

This project answers key business questions:

- What percentage of loans are performing well?
- Which regions generate the highest funding?
- How does employment length affect lending?
- What loan purposes dominate the portfolio?
- Is repayment exceeding funded amounts?

---

# 📂 Dataset Overview

**Dataset:** `financial_loan.xlsx`

The dataset includes loan-level financial information such as:

- Issue Date  
- Loan Amount  
- Funded Amount  
- Total Amount Received  
- Interest Rate  
- Debt-to-Income Ratio (DTI)  
- Loan Term  
- State  
- Employment Length  
- Home Ownership  
- Loan Purpose  
- Loan Status  

Each row represents an individual loan record.

---

# 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Plotly  
- Jupyter Notebook  

---

# ⚙️ Project Workflow

## 1️⃣ Data Cleaning

- Converted issue dates to datetime format  
- Handled missing values  
- Standardized categorical variables  
- Corrected numeric formatting issues  

---

## 2️⃣ Feature Engineering

- Created **Year-Month column** for time-series analysis  
- Categorized loans into:
  - ✅ Good Loans  
  - ❌ Bad Loans  
- Generated state-level, purpose-level, and employment-level aggregations  

---

## 3️⃣ KPI Design & Calculation

# 📊 Key Performance Indicators (KPIs)

## 📌 Overall Portfolio Metrics

| KPI | Value |
|------|--------|
| Total Loan Applications | 38,576 |
| Total Funded Amount | $435.76M |
| Total Amount Received | $473.07M |
| Average Interest Rate | 12.05% |
| Average DTI | 13.33% |

---

## ✅ Good Loan Metrics

- Good Loan Percentage: **86.17%**
- Good Loan Applications: 33,243
- Good Loan Funded Amount: $370.22M
- Good Loan Total Received: $435.79M

---

## ❌ Bad Loan Metrics

- Bad Loan Percentage: **13.82%**
- Bad Loan Applications: 5,333
- Bad Loan Funded Amount: $65.53M
- Bad Loan Total Received: $37.28M

---

# 📈 Exploratory Analysis & Visualizations

## 1️⃣ Monthly Trends Analysis

- Monthly Number of Applications  
- Monthly Funded Amount  
- Monthly Received Amount  

Purpose:
- Detect seasonality  
- Track lending growth  
- Compare disbursed vs received amounts  

---

## 2️⃣ Regional Analysis (State-Level)

Analyzed:

- Total Applications by State  
- Total Funded Amount by State  
- Total Received Amount by State  

---

## 3️⃣ Loan Term Distribution

- Applications by Loan Term  
- Funded Amount by Loan Term  
- Received Amount by Loan Term  

---

## 4️⃣ Employment Length Impact

- Applications by Employment Length  
- Funded Amount by Employment Length  
- Received Amount by Employment Length  

---

## 5️⃣ Loan Purpose Breakdown

- Applications by Purpose  
- Funded Amount by Purpose  
- Received Amount by Purpose  

---

## 6️⃣ Home Ownership Analysis

Evaluated how home ownership affects:

- Loan Applications  
- Funded Amount  
- Repayment Trends  

---

# 📊 Key Insights

- 86% of loans fall under the Good Loan category  
- Total received amount exceeds funded amount  
- Certain states dominate lending distribution  
- Employment stability impacts lending behavior  
- Loan purpose influences funding patterns  

---

# 💼 Business Value Delivered

This project demonstrates how structured EDA can help:

- Assess portfolio health  
- Identify high-risk segments  
- Improve credit risk evaluation  
- Support data-driven lending strategies  
- Optimize regional loan distribution  

---

# 🧠 Skills Demonstrated

- Exploratory Data Analysis (EDA)  
- Financial KPI Design  
- Data Cleaning & Transformation  
- Feature Engineering  
- Time-Series Analysis  
- Risk Segmentation  
- Data Visualization  
- Business Insight Communication  

---

# 📁 Project Structure

```
End-to-End-Loan-EDA-Python/
│
├── financial_loan.xlsx
├── Loan_EDA_Notebook.ipynb
├── Loan Data Analysis Project Report.pdf
├── Loan-Data-Analysis-Project_pptx.pdf
└── README.md
```

---

# ▶️ How to Run

1. Clone the repository  
2. Install required libraries:

```
pip install pandas numpy matplotlib plotly
```

3. Open Jupyter Notebook  
4. Run all cells  

---

# 🔮 Future Improvements

- Build interactive dashboard using Power BI or Streamlit  
- Implement credit risk prediction model  
- Add default probability classification  
- Automate KPI reporting  

---

# 🏁 Conclusion

This project showcases an end-to-end financial loan portfolio analysis using Python. Through systematic data cleaning, KPI calculation, and visualization, raw financial data is converted into meaningful business insights that support lending decisions.


# 👤 Author

Onkar Ithape
Aspiring Data Analyst
email - onkarithape.work@gmail.com