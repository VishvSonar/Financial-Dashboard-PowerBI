# Financial Performance Dashboard – Power BI

## Overview
This project is an interactive **Financial Performance Dashboard** built in **Power BI** to analyze a company’s financial health using monthly data.  
It demonstrates data cleaning, DAX calculations, KPI design, and dashboard visualization skills suitable for entry-level Data Analyst roles.

---

## Objective
To build a dynamic dashboard that helps monitor:
- Revenue & Profit trends
- Budget vs Actual performance
- Cash Flow movement
- Product/Service contribution
- Receivables aging & overdue risk

---

## Dataset
Monthly CSV financial dataset containing:
Month, Region, Product/Service, Revenue, COGS, Gross Profit, Opex, EBITDA,  
Cash Inflows, Cash Outflows, Receivables Aging (Days), Payables Aging (Days), Revenue Budget.

---

## Data Preparation
- Converted **Month** to Date format for time analysis.
- Ensured correct numeric data types for financial fields.
- Created **Receivable Aging Buckets** (0–30, 31–60, 61–90, 90+).
- Validated dataset and handled formatting issues.

---

## Key DAX Measures
- **Net Cash** = Cash Inflows − Cash Outflows  
- **Gross Margin %** = Gross Profit / Revenue  
- **EBITDA %** = EBITDA / Revenue  
- **Budget Variance %** = (Actual − Budget) / Budget

---

## Dashboard Features
**KPIs**
- Revenue
- Gross Margin %
- EBITDA %
- Net Cash

**Visuals**
- Revenue vs Profit Trend (Line Chart)
- Budget vs Actual Variance (Column Chart)
- Product/Service Performance (Bar Chart)
- Cash Flow Waterfall
- Receivables Aging Distribution

**Interactivity**
- Date Range Filter
- Region Filter
- Product/Service Filter
- Dynamic visual updates

---

## Sample Insights
- Some months showed negative budget variance indicating under-performance.
- Few products/services contributed majority revenue.
- Most receivables were within 0–30 days showing healthy collections.

---

## Tools Used
- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- CSV/Excel Data Processing  
- GitHub (Portfolio Hosting)

---

## Repository Contents
- `Financial_Dashboard.pbix` – Power BI dashboard file  
- `Financial_Dashboard_One_Page_Report.pdf` – Project summary  
- `Dashboard image` – Preview image

---

## Skills Demonstrated
Data Cleaning • DAX • KPI Analysis • Dashboard Design • Financial Analytics • Interactive Visualization

---

## Conclusion
This project converts raw financial data into meaningful business insights using Power BI.  
It showcases practical dashboard development and analytical skills aligned with real-world data analyst responsibilities.
