Apple Inc. Financial Analysis (2009–2024)

Status: Work in Progress

ACCA-aligned financial ratio analysis and interactive dashboard, using Apple's annual financial data from 2009–2024. Built to demonstrate practical accounting/finance analytical skills using Excel and Power BI.

Objective

Analyze 16 years of Apple's financial performance to identify profitability trends, financial health, and year-over-year growth patterns — combining traditional accounting analysis (Excel) with interactive visualization (Power BI).

Data Source


Base dataset: Apple financial statement data (Revenue, Net Income, EBITDA, Total Assets, Total Liabilities, EPS, and related metrics), 2009–2024, via Kaggle.
Supplementing with Current Assets/Current Liabilities figures sourced directly from Apple's SEC 10-K filings, to enable liquidity ratio analysis not present in the base dataset.


Planned Work

Data Cleaning (Excel / Power Query)


 Strip currency symbols and thousands separators from numeric fields (all values currently stored as text)
 Convert percentage fields (e.g. Gross Margin) to true numeric values
 Standardize Year field as a date/numeric type
 Source and append Current Assets / Current Liabilities from Apple 10-K filings (2009–2024)
 Validate data against at least one year of official Apple financial statements for accuracy


Excel Analysis


 Identify the most profitable year (by Net Income and by Net Margin) and explain the drivers
 Calculate profitability ratios: Gross Margin, Net Margin, Return on Assets (ROA), Return on Equity (ROE)
 Calculate solvency ratios: Debt-to-Equity, Debt-to-Assets
 Calculate liquidity ratios: Current Ratio, Quick Ratio (pending 10-K data supplement)
 Year-over-year growth rate analysis (Revenue, Net Income, EPS)


Power BI Dashboard


 Revenue, Net Income, and EBITDA trends (2009–2024)
 Profitability ratio visualization over time
 Growth vs. decline year highlighting (visual flag for down years, e.g. 2016, 2019)
 EPS and share price trend overlay
 Summary page: key financial health indicators at a glance


Documentation


 Case study write-up (1–2 pages): methodology, key findings, business interpretation
 Data cleaning report: what was cleaned and why
 Final README update with dashboard screenshots and findings summary


Tools


Excel (ratio calculations, data cleaning)
Power BI (dashboard, visualization)
