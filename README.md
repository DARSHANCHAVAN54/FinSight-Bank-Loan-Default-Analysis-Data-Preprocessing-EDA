# 🏦 FinSight Bank Loan Default Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a bank loan dataset to identify factors contributing to loan defaults. The analysis includes data cleaning, feature engineering, borrower behavior analysis, and macroeconomic impact assessment to generate actionable business insights for risk management.

## 🛠️ Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **SciPy**
* **Jupyter Notebook**

## 📊 Key Steps

### Data Cleaning & Preprocessing

* Handled missing values
* Treated outliers using Winsorization
* Fixed structural data issues

### Feature Engineering

Created business-focused features such as:

* EMI-to-Income Ratio
* Delinquency Severity Score
* Collateral Coverage Ratio
* Loan-to-Income Ratio
* Risk & Financial Health Indicators

### Macroeconomic Analysis

* RBI Repo Rate impact analysis
* COVID-19 economic shock analysis
* Default trend evaluation

## 💡 Key Insights

* **CIBIL Score Alone Isn't Enough:** Significant overlap exists between good and bad borrowers.
* **Repo Rate Lag Effect:** Higher RBI repo rates increase default risk after a time delay.
* **Loan Purpose Matters:** Debt consolidation loans show higher default rates than secured loans.
* **Repayment Burden Matters:** Higher EMI-to-Income ratios are strongly linked to defaults.

## 🚀 How to Run

```bash
git clone <repository-url>
cd FinSight-Bank-Loan-Default-Analysis
pip install pandas numpy matplotlib seaborn scipy
jupyter notebook
```

## 🎯 Conclusion

The analysis shows that loan default prediction requires a combination of borrower financial behavior, credit history, engineered risk metrics, and macroeconomic indicators. These insights can be used to build robust machine learning models for credit risk assessment.
