Apple Inc. Financial Analysis (2009-2024)

Status: Work in Progress

This is a financial analysis project I'm building using Apple's annual financial data from 2009 to 2024. I'm using it to practice and demonstrate the kind of accounting and financial analysis skills I'm developing through my ACCA studies, combined with Excel and Power BI.

Objective

I want to look at 16 years of Apple's financial performance and figure out how profitable they've been over time, how financially healthy they are, and how their numbers have grown or declined year over year. I'm doing the number crunching and ratio work in Excel, then building a dashboard in Power BI to visualize everything.

Data Source

The base data (Revenue, Net Income, EBITDA, Total Assets, Total Liabilities, EPS, and a few other metrics) is from Apple Financials 2009-2024 on Kaggle, covering 2009 to 2024.

One thing I noticed early on is that the dataset doesn't include Current Assets or Current Liabilities, which means I can't calculate liquidity ratios from it alone. So I'm going through Apple's actual SEC 10-K filings to pull those numbers myself and add them in.

Planned Work

Data Cleaning (Excel / Power Query)


Clean up the numeric fields since everything is currently stored as text with dollar signs and commas in it
Convert the percentage fields, like Gross Margin, into actual numbers I can calculate with
Fix the Year column so it's a proper date or numeric field
Add in the Current Assets and Current Liabilities figures I'm sourcing from the 10-K filings
Double check my numbers against at least one year of Apple's official financial statements to make sure everything lines up


Excel Analysis


Figure out which year was Apple's most profitable, both by Net Income and by Net Margin, and understand what drove it
Calculate profitability ratios: Gross Margin, Net Margin, Return on Assets, and Return on Equity
Calculate solvency ratios: Debt to Equity and Debt to Assets
Calculate liquidity ratios: Current Ratio and Quick Ratio, once I've added the 10-K data
Look at year over year growth for Revenue, Net Income, and EPS


Power BI Dashboard


Show Revenue, Net Income, and EBITDA trends from 2009 to 2024
Visualize how the profitability ratios have moved over time
Highlight the years where the company grew versus the years it dipped, like 2016 and 2019
Overlay EPS against share price
Build a summary page that shows the key financial health indicators at a glance


Documentation


Write a short case study, one to two pages, covering my methodology, what I found, and what it means from a business perspective
Write up a short data cleaning report explaining what I cleaned and why
Update this README once everything's done, with dashboard screenshots and a summary of the findings


Tools

Excel for the ratio calculations and data cleaning. Power BI for the dashboard and visualizations.
