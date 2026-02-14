#  IMF Financial Soundness Analysis  
> A country-wise time series analysis of banking sector stability using real IMF FSI data.

---

##  Overview

This project performs a multi-country financial soundness assessment using official **Financial Soundness Indicators (FSIs)** from the **International Monetary Fund (IMF)**. It analyzes key regulatory and risk metrics across countries like **Brazil, France, Germany, and Japan**, tracking trends from **2005 to 2025**.

The project focuses on visualizing and interpreting **Basel III–aligned indicators** such as:
- Capital adequacy
- Asset quality (NPLs)
- Earnings and profitability
- Liquidity ratios
- Market risk sensitivity

---

##  Objectives

- Leverage real IMF data to assess financial health across countries  
- Track temporal trends and identify risk signals  
- Align indicator selection with Basel III regulatory themes  
- Present insights through clean visualizations and executive summaries

---

##  Tools & Technologies

- **Python** (Pandas, Matplotlib, Seaborn)
- **Jupyter Notebook** (data cleaning, visualization)
- **PowerPoint** (final presentation/reporting)
- Data Source: [IMF Financial Soundness Indicators](https://data.imf.org/)

---

##  Key Indicators Used

| Code        | Indicator Description                                          |
|-------------|---------------------------------------------------------------|
| FSANL_PT    | Non-performing Loans to Total Gross Loans (%)                |
| FSKNL_PT    | Net NPLs to Capital (%)                                       |
| FSERA_PT    | Return on Assets (%)                                          |
| FSKRTC_PT   | Tier 1 Capital to RWA (%)                                     |
| FSLS_PT     | Liquid Assets to Short-Term Liabilities (%)                  |
| FSSNO_PT    | Financial System Soundness Indicator (Composite Stress Score)|

---

##  Countries Analyzed

- Brazil  
- France  
- Germany   
- Japan  

---

##  Visualizations & Insights

Each metric was plotted as a time series by country, with accompanying insights:
- Trends in capital adequacy and liquidity post-2008 and post-COVID.
- Comparative performance of emerging vs developed economies.
- Stress signals based on composite financial risk indicators.

 [See the full presentation](https://github.com/intheperkofextinction/IMF-financial-soundness-analysis/blob/main/FINANCIAL%20SOUNDNESS%20ANALYSIS.pdf)

---
# IMF Financial Soundness Analysis Dashboard

<img width="1640" height="1150" alt="image" src="https://github.com/user-attachments/assets/73a86d2e-1fc3-4332-be80-77b7f038684a" />


##  Overview
This Power BI dashboard analyzes banking sector stability using IMF Financial Soundness Indicators.

##  Key Metrics
- Tier 1 Capital Ratio
- Non-Performing Loan (NPL) Ratio
- Liquidity Ratio
- Return on Assets (ROA)
- FX Open Position

##  Visualizations
- Asset Quality Trend (NPL Trend)
- Banking Sector Risk Scatter (Capital vs NPL)
- NPL vs ROA Comparison
- Tier 1 Capital Comparison by Country

##  Tools Used
- Power BI
- Excel
- DAX
- Data Modeling

##  Countries Analyzed
Brazil, France, Germany, Japan

##  Insights
- Germany shows strongest capital position.
- France & Brazil show higher NPL levels.
- Japan shows lower NPL but moderate capital adequacy.

---



##  Key Takeaways

- Basel-aligned indicators are crucial for tracking global financial resilience.
- Real-world IMF data reveals unique vulnerabilities in emerging markets.
- Systematic visualization uncovers macro-financial risk patterns.

---

##  Project Structure
```
├── Cleaned_IMF_FSI_for_analysis.csv # Cleaned dataset
├── FSI_TimeSeries_Analysis.ipynb # Time series and insights
├── Financial_Soundness_Analysis.pptx # Final report (visual summary)
└── README.md
```
---

##  Author

**Amal S.**  
Aspiring Financial Data Analyst | Python • Power BI • SQL  
LinkedIn : linkedin.com/in/amal-s-9a5b86310

[GitHub](https://github.com/intheperkofextinction)

---

##  Note

> This project was independently built using official IMF data for learning and demonstration purposes. It is not affiliated with the IMF or any financial institution.
 If you found this useful, feel free to connect with me!

---




