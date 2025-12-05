#  Political Volatility as an Asset Class
### The 'Smart Seasonal' Strategy for Brazil

**Author:** Vinicius Luiz 

---

## 📊 Executive Summary
Everyone talks about political risk. Few measure it.
This project uses a Python algorithm to analyze the last **6 Brazilian election cycles (2002-2022)**. The data reveals a clear **'Risk-Off' window between May and August** where Cash (Selic) consistently beats Equities.

## 🧠 The Strategy
Historical data shows that the mid-year campaign window delivers negative returns due to uncertainty. We implement a quantitative rotation:

1.  **RISK-ON (Jan-Apr & Sep-Dec):** Long exposure to Ibovespa.
2.  **RISK-OFF (May-Aug):** Tactical rotation to 100% Risk-Free Rate (Selic/CDI).

## 📁 Contents
* `Allez_Invest_Book_Official.pdf`: The full institutional report with charts and rationale.
* `b3_analise.ipynb`: The Python source code used for data extraction (Yahoo Finance API), processing (Pandas), and visualization (Matplotlib).

---
*Disclaimer: This study is strictly a cycle analysis and contains no political assessment. Just data.*
