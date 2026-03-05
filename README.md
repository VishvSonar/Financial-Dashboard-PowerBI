Financial Performance Dashboard (Power BI)
Overview

This project presents a Financial Performance Dashboard developed in Power BI to analyze key financial metrics including revenue, profitability, budget performance, receivables aging, and cash flow.

The dashboard enables business users to monitor financial performance across regions and product/service categories while providing interactive analysis through filters and drill-down functionality.

Objectives

The main objectives of this dashboard are:

Track overall financial performance using key financial KPIs

Compare actual revenue against planned budget targets

Identify revenue contribution by product/service categories

Monitor receivables aging to assess potential collection delays

Analyze monthly cash flow trends

Provide interactive data exploration through filters and drill-down features

Key Metrics

The dashboard focuses on the following financial KPIs:

Total Revenue

Gross Margin %

EBITDA %

Net Cash

These indicators help measure revenue performance, operational profitability, and financial liquidity.

Dashboard Components
Revenue and Profit Trend

Displays revenue and gross profit trends over time with drill-down capability (Year → Quarter → Month) to analyze financial performance at different time levels.

Budget vs Actual Revenue Variance

Shows the percentage difference between budgeted revenue and actual revenue to evaluate whether financial targets are being achieved.

Product / Service Performance

Analyzes revenue distribution across product and service categories to identify top-performing segments.

Receivables Aging Analysis

Groups receivables into aging buckets (0–30, 31–60, 61–90, 90+ days) to highlight overdue payments and potential collection risks.

Cash Flow Waterfall

Visualizes monthly net cash flow by comparing cash inflows and outflows, helping track liquidity trends.

Logic Used

The financial calculations in the dashboard are based on the following logic:

Gross Margin %
Gross Margin % = (Gross Profit ÷ Revenue) × 100

EBITDA %
EBITDA % = (EBITDA ÷ Revenue) × 100

Net Cash
Net Cash = Cash Inflows – Cash Outflows

Budget Variance %
Measures the percentage difference between Actual Revenue and Budgeted Revenue.

Receivables Aging Buckets
Receivables were categorized into aging groups to identify payment delays.

Interactivity

The dashboard includes several interactive features to improve analysis:

Region filter for geographical analysis

Product/Service filter for category-level insights

Year filter for time-based analysis

Drill-down functionality in trend charts (Year → Quarter → Month)

These features allow users to dynamically explore the dataset and analyze performance from different perspectives.

Data Validation

To ensure data accuracy, validation checks were implemented:

Gross Profit Validation
Revenue – COGS = Gross Profit

EBITDA Validation
Gross Profit – Opex = EBITDA

Both checks return 0.00, confirming that the calculations in the dataset are consistent.

Assumptions

The following assumptions were considered while building the dashboard:

All financial values are recorded in the same currency

Revenue Budget values represent planned revenue targets

Receivables Aging represents the number of days invoices remain outstanding

The Month column represents the reporting period used for time-based analysis

Tools and Technologies

Power BI
DAX
Excel / CSV Dataset

Repository Contents

Financial_Dashboard.pbix – Power BI dashboard file
dataset.csv – Source dataset
dashboard_preview.png – Dashboard image

Author

Vishv Sonar
