# Tariff War Fund Risk Analysis

## Overview
This project analyzes how global tariff wars and trade tensions impact the performance, volatility, and resilience of equity mutual funds and ETFs. Using a dataset of 300+ global funds, the analysis evaluates tariff exposure, supply-chain resilience, sector and geographic sensitivity, and risk–return trade-offs to develop a data-driven investment strategy.

The project is designed from the perspective of a portfolio manager navigating trade uncertainty, with a focus on **risk management, resilience, and medium- to long-term investment decision-making** rather than short-term return prediction.

---

## Problem Statement
Global trade has become increasingly volatile due to tariffs, retaliatory measures, and supply-chain disruptions. Funds with high tariff exposure may face performance headwinds, while those with diversified supply chains and geographic resilience may outperform.

The objective is to:
- Identify sectors and funds most vulnerable to tariff shocks  
- Highlight resilient investment opportunities  
- Quantify the impact of tariff exposure on returns and risk  
- Develop an actionable, data-backed investment strategy and horizon  

---

## Dataset
- **300+ global equity mutual funds and ETFs**
- Complete data coverage (no missing values)
- Key variables include:
  - Tariff exposure (Tariff Risk Score, Import Exposure, China Exposure)
  - Resilience metrics (Trade War Resilience, Supply Chain Vulnerability)
  - Performance (1Y, 3Y returns)
  - Risk (Volatility, Max Drawdown)
  - Fund characteristics (AUM, Expense Ratio, Fund Type, Sector, Geography)

---

## Methodology

### 1. Data Preparation & Sanity Checks
- Verified record counts and data completeness  
- Validated economic ranges for exposure, return, and risk metrics  
- Created derived variables:
  - Tariff Risk Categories (Low / Medium / High)
  - Resilience Buckets
  - AUM Size Buckets  

---

### 2. Exploratory Data Analysis (EDA)
Key analyses included:
- Tariff risk distribution across sectors and geographies  
- Relationship between tariff exposure and returns  
- Impact of resilience and supply-chain vulnerability on performance  
- Volatility and drawdown patterns by sector  
- Identification of outliers (resilient outperformers and vulnerable underperformers)

---

### 3. Modeling & Factor Analysis
- OLS regression models to assess:
  - Tariff exposure vs. short-term returns
  - Tariff exposure and resilience vs. risk (volatility)
- Interaction analysis (Tariff Risk × Resilience)
- Diagnosed multicollinearity and interpreted results conservatively

**Key insight:**  
Tariff exposure has limited power in explaining short-term returns but plays a meaningful role in shaping **risk and volatility**, supporting a longer investment horizon.

---

### 4. Dashboard (Excel)
An interactive Excel dashboard was built using pivot tables and slicers to:
- Visualize tariff risk across sectors and regions  
- Compare returns, volatility, and resilience  
- Enable filtering by tariff risk, sector, geography, fund type, and AUM  

---

### 5. Fund Selection & Strategy
Funds were shortlisted into three categories:
- **Low Tariff Risk + Strong Returns**
- **High Resilience Funds**
- **Balanced Risk–Return Profile**

Shortlists were exported as CSV files for transparency and reproducibility.

---

## Key Insights
- Tariff wars affect **risk and volatility more than short-term returns**
- Resilience and diversification help mitigate tariff shocks over time
- Developed markets show relatively higher stability during trade tensions
- Investment decisions should prioritize **risk control and structural resilience**

---

## Investment Recommendation
- **Proposed investment horizon:** ~5 years  
- **Rebalancing approach:** Annual, with event-driven reviews based on tariff or policy announcements  
- **Strategy focus:** Diversified, resilience-oriented fund selection rather than short-term return chasing  

---

## Tools & Technologies
- **Python:** Pandas, NumPy, Statsmodels  
- **Excel:** Pivot Tables, Interactive Dashboards  
- **Techniques:** EDA, Regression Analysis, Risk Modeling, Data Visualization  

---


---

## Disclaimer
This project is for **educational and analytical purposes only** and does not constitute financial advice.

---

## Author
Reezwan Parvez  
Background in Data Science, Engineering, and MBA with a focus on data-driven investment and risk analysis.

