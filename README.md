# 3-Statement Financial Model

## Overview
Apex Solutions Inc. is a global technology company operating across three business segments: Software, Hardware, and IT Services. As part of an equity research analysis, this model was developed to project the company's financial performance over a 5-year period, assess its growth trajectory, and evaluate key financial health metrics including profitability, liquidity, and debt management.

The model integrates all three financial statements — Income Statement, Balance Sheet, and Cash Flow Statement — ensuring full reconciliation across projections.

## What's Modeled
- Revenue projections across 3 business segments with segment-level growth rate assumptions sourced from management's MD&A
- COGS and gross margin analysis by segment
- SG&A expense forecasting as a percentage of revenue
- Depreciation schedule modeled as a percentage of revenue, linked to CapEx and Net PPE
- Working capital modeling including accounts receivable, inventory, and accounts payable turnover ratios
- Debt schedule with annual repayments and issuances, with interest expense circularity resolved via iterative calculation
- Full cash flow reconciliation ensuring ending cash on the Cash Flow Statement ties to the Balance Sheet

## Tools Used
- Microsoft Excel

## Key Assumptions (from MD&A)
| Driver | Assumption |
|---|---|
| Software Revenue Growth | 20% annually |
| Hardware Revenue Growth | 18% annually |
| IT Services Revenue Growth | 16% annually |
| Software COGS | 50% of segment revenue |
| Hardware COGS | 48% of segment revenue |
| IT Services COGS | 50% of segment revenue |
| SG&A | 15% of total revenue |
| Depreciation | 4.4% of total revenue |
| Term Loan Interest Rate | 9.0% |
| Cash Deposit Interest Rate | 3.0% |
| Receivables Collection Period | 19 days |
| Inventory Processing Period | 70 days |
| Supplier Payment Period | 48 days |

## Model Structure
The workbook contains the following sheets:
- **Index** — navigation guide
- **Income Statement** — historical actuals and 5-year projections with segment-level drivers
- **Balance Sheet** — assets, liabilities, and equity with balance check
- **Cash Flow Statement** — operating, investing, and financing activities reconciled to Balance Sheet
- **Depreciation & CapEx** — fixed asset schedule linked to Balance Sheet
- **Working Capital** — turnover
