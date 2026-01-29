# Loan Distribution Analysis: Garima Bikas Bank Limited

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nandikathapa4-gif/loan-distribution-analysis-garima-bank/blob/main/Untitled0.ipynb)

## Project Overview
This repository contains a Jupyter notebook analyzing the loan distribution and portfolio trends of **Garima Bikas Bank Limited (GBBL)**, a national-level development bank in Nepal. As part of my Bachelor of Business Studies (BBS) project at Prithvi Narayan Campus, Tribhuvan University, this work examines loan disbursement patterns from fiscal years **2076/77 to 2079/80**, focusing on key economic indicators like year-over-year (YoY) growth, portfolio composition, and volatility.

The analysis uses Python-based data processing to derive insights into banking efficiency, risk management, and sector-specific trends (e.g., margin lending volatility). This project demonstrates my ability to handle real-world financial data, apply statistical methods (e.g., coefficient of variation), and interpret results in the context of Nepal's banking sector—skills transferable to international economics and data science applications.

## Key Objectives
* **Evaluate loan type distributions** (e.g., Term Loans, Overdraft Loans, Margin Lending) using stacked area charts and line plots.
* **Calculate YoY growth rates** to identify trends, such as the 337% surge in Margin Lending in 2077 followed by volatility.
* **Assess overall portfolio risk** through metrics like standard deviation (NPR 146.76 million) and CV (0.7357), highlighting potential insolvency risks from negative cash flows.
* **Provide actionable insights** for bank management, such as stress testing for volatile segments.

## Data Sources
* Extracted from GBBL's annual reports and internal datasets (fiscal years 2076/77–2079/80).
* Focus on loan categories, amounts, and borrower counts; processed to exclude irrelevant patterns (e.g., via regex filtering).

## Methodology
* **Data Cleaning:** Used `pandas` to melt, filter, and pivot raw data, excluding non-loan entries (e.g., "Capital Adequacy") with regex patterns.
* **Analysis:**
    * **YoY Growth:** Computed percentage changes for individual loan types and total portfolio.
    * **Visualization:** Stacked area charts (`matplotlib`) for composition; line plots (`seaborn`) for trends like Margin Lending.
    * **Volatility:** Calculated CV for each loan type (e.g., Overdraft Loan at 0.652) and overall portfolio.
* **Insights:** Interpreted results economically, e.g., linking Margin Lending fluctuations to market sentiment or regulatory changes.

## Sample Outputs
* **Stacked Area Chart:** Shows evolving loan mix over years.

* **YoY Growth for Margin Lending:**

| Fiscal Year | Growth Rate |
| :--- | :--- |
| 2077 | 336.97% |
| 2078 | -21.59% |
| 2079 | 48.62% |
| 2080 | 14.73% |

* **Portfolio Volatility:** High CV (0.7357) indicates need for diversified risk strategies.


## Technologies Used
* **Python Libraries:** `pandas` (data manipulation), `matplotlib`/`seaborn` (visualization), `re` (regex filtering).
* **Environment:** Google Colab (Python 3).
* **Skills Demonstrated:** Data wrangling, statistical analysis, economic interpretation, visualization.
