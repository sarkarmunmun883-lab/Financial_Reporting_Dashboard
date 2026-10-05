# Financial Reporting & Management Dashboard

An end-to-end financial reporting model built in **Microsoft Excel**. This portfolio project transforms transaction-level accounting data into management reports covering profitability, budget performance, cash flow, and key financial ratios.

![Project cover](assets/project-cover.png)

## Project overview

The workbook contains **4,000 transaction records** covering **April–September 2026**. It brings together a chart of accounts, budget data, monthly financial statements, variance analysis, cash-flow reporting, financial ratios, and a management dashboard.

> **Note:** The workbook uses realistic/sample transaction data for demonstration. Review and replace the data before using it for real business reporting.

## Workbook contents

| Worksheet | Purpose |
|---|---|
| `README` | In-workbook project overview |
| `Chart_of_Accounts` | Account codes, names, categories, statement mapping, and departments |
| `Raw_Transactions` | Transaction-level accounting data (4,000 records) |
| `Budget` | Monthly budget data |
| `P&L` | Monthly profit and loss reporting |
| `Budget_vs_Actual` | Budget, actual, variance, and variance percentage |
| `Cash_Flow` | Monthly cash inflows, outflows, and net cash flow |
| `Financial_Ratios` | Gross margin, net margin, expense ratio, and revenue growth |
| `Dashboard` | Consolidated management dashboard |

## Reporting workflow

```text
Raw Transactions + Chart of Accounts + Budget
                    |
                    v
             Monthly P&L
                    |
          +---------+---------+
          |                   |
          v                   v
    Budget vs Actual      Cash Flow
          |                   |
          +---------+---------+
                    v
             Financial Ratios
                    |
                    v
           Management Dashboard
```

## Key analysis

- **Profit & Loss:** revenue, cost of goods sold (COGS), gross profit, gross margin, operating expenses, net profit, and net margin.
- **Budget vs Actual:** planned versus actual performance, absolute variance, and variance percentage.
- **Cash Flow:** monthly cash inflows, outflows, and net cash flow.
- **Financial Ratios:** gross margin, net margin, operating expense ratio, and month-over-month revenue growth.
- **Management Dashboard:** headline financial KPIs and monthly performance visuals.

## Tools and skills demonstrated

- Microsoft Excel and formula-driven reporting
- `SUMIFS`, `IFERROR`, and `EDATE`
- Financial modelling and management reporting
- Profitability and cash-flow analysis
- Budget variance analysis
- KPI design and dashboard visualization
- Structured transaction data and chart-of-accounts mapping

## Getting started

1. Download or clone this repository.
2. Open `Project_4_Financial_Reporting_Dashboard.xlsx` in Microsoft Excel.
3. Start with the `Dashboard` sheet for the management overview.
4. Review `Raw_Transactions`, `Chart_of_Accounts`, and `Budget` to understand the source data.
5. Explore the reporting sheets for supporting calculations.

For best compatibility, open the workbook in a recent desktop version of Microsoft Excel and allow formulas to recalculate.

## Screenshots

The `screenshots/` folder is reserved for workbook screenshots. To add a real dashboard screenshot:

1. Open the workbook and select the `Dashboard` worksheet.
2. Capture the dashboard area.
3. Save the image as `screenshots/dashboard.png`.
4. Add the following Markdown to this section:

```markdown
![Excel dashboard](screenshots/dashboard.png)
```

## Future enhancements

- Power Query-based import and refresh automation
- Department and date filters
- Scenario planning and financial forecasting
- More detailed departmental profitability analysis
- Power Pivot / Data Model integration
- Power BI implementation

## Project information

**Project:** Financial Reporting & Management Dashboard  
**Platform:** Microsoft Excel  
**Reporting period:** April–September 2026  
**Dataset:** 4,000 sample transactions  
**Type:** Portfolio project — Financial Reporting & Data Analytics

---

*Created as a practical demonstration of Excel-based financial modelling, reporting, and dashboard development.*
