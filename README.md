# Bank-Loan-Analytics.Dashboard

# 🏦 Bank Loan Analytics Dashboard

An end-to-end data analytics project built to evaluate bank loan portfolios, track financial key performance indicators (KPIs), and assess risk profiles using Power BI, SQL, and Excel.

## 📊 Project Overview
This project provides comprehensive insights into bank lending operations. It helps stakeholders monitor total loan applications, funded amounts, amounts received, average interest rates, and debt-to-income (DTI) ratios across various dimensions such as loan purpose, state, home ownership, and term.

### Key Features:
* **Overview Page:** Tracks overall monthly loan trends, regional state-wise distribution, loan terms (36 vs 60 months), home ownership breakdown, and purpose-based loan categories (e.g., Debt Consolidation, Credit Card)[cite: 1].
* **Summary Page:** Splits performance into **Good Loans** vs. **Bad Loans**, monitoring repayment trends, charged-off rates, and funded amount versus repayment comparisons[cite: 2].

 ## 📸 Dashboard Screenshots

### Overview Dashboard
![Overview Dashboard](Screenshots/overview.png)[cite: 1]

### Summary Dashboard
![Summary Dashboard](Screenshots/summary.png)[cite: 2]

## 🛠️ Tech Stack & Tools
* **Data Visualization:** Power BI Desktop
* **Data Processing & Modeling:** SQL, Excel, DAX
* **Version Control:** Git & GitHub

## 📂 Repository Structure

* **`bank-loan-analytics-powerbi/`** — Root folder of the project repository.
* **`Dashboard/`** — Folder containing the interactive Power BI report.
  * `bank_loan_dashboard.pbix` — Main Power BI source file containing visuals, layouts, and DAX calculations.
* **`Data/`** — Folder containing the underlying project dataset.
  * `financial_loan.csv` — Raw dataset containing loan records, interest rates, DTI ratios, and status data.
* **`Screenshots/`** — Folder containing dashboard visual previews for documentation.
  * `overview.png` — Screenshot of the main Overview Dashboard page[cite: 1].
  * `summary.png` — Screenshot of the Good vs. Bad Loan Summary page[cite: 2].
* **`README.md`** — Comprehensive project documentation file.

  ## Author
  Aqudas Rizwan.


## 🚀 How to Use / View This Project
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/bank-loan-analytics-powerbi.git](https://github.com/your-username/bank-loan-analytics-powerbi.git)
