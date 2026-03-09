
# Insurance Portfolio Simulation & Risk Analysis

This project simulates an insurance portfolio and analyzes its financial performance using **SQL and Python**. The analysis focuses on premium revenue, claim costs, loss ratios, and potential future liabilities.

## Overview

Two datasets were generated to model an insurance portfolio:

- **Policy Sales Data** – policies sold during 2024 including customer details, vehicle information, policy tenure, and premium.
- **Claims Data** – simulated insurance claims based on predefined rules for 2025 and early 2026.

The objective of the analysis is to evaluate portfolio profitability and understand how factors such as **policy tenure and claim frequency** influence insurance risk.

## Key Analysis Performed

The following analytical tasks were carried out:

- Calculation of total premium collected from the portfolio
- Monthly claim cost trend analysis
- Claim-to-premium ratio by policy tenure
- Claim ratio by policy purchase month
- Estimation of future claim liabilities
- Earned premium and remaining premium calculations
- Portfolio loss ratio analysis
- Impact analysis of increased claim frequency

## Key Insights

- **3-year policies appear to be the most profitable**, having the lowest claim-to-premium ratio.
- Claim costs remain relatively stable during **2025**, with a noticeable spike in **early 2026** due to additional claims from 4-year policies.
- The portfolio loss ratio exceeds **1**, meaning claim costs are higher than premium revenue under the simulated assumptions.
- A large portion of potential claim liability remains from vehicles that have not yet filed claims.
- Increasing claim frequency significantly worsens portfolio profitability.

## Tools Used

The project was implemented using:

- **Python (Pandas)**
- **SQLite / SQL**
- **Matplotlib / Seaborn**
- **Google Colab**

## Conclusion

This project demonstrates how **data analytics techniques can be applied to insurance portfolio analysis** to evaluate profitability, assess risk exposure, and estimate future financial liabilities.
