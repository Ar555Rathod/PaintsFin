# 🎨 Indian Paints & Coatings Industry: Comparative Financial Statement & Ratio Analysis

[![Domain](https://img.shields.io/badge/Domain-Corporate_Finance_%26_Equity_Research-1f77b4.svg)](#)
[![Sector](https://img.shields.io/badge/Sector-Paints_%26_Coatings_(India)-orange.svg)](#)
[![Format](https://img.shields.io/badge/Models-Excel_%26_PDF_Report-success.svg)](#)
[![Accounting Standard](https://img.shields.io/badge/Standards-Ind_AS_Compliant-blueviolet.svg)](#)

A comprehensive financial accounting and ratio analysis evaluating the performance, operating efficiency, capital structure, and profitability of **five leading listed Indian paint and coating companies**.

---

## 📌 Executive Summary

The Indian paints and coatings industry is an oligopolistic, high-growth sector characterized by high brand loyalty, strong dealer distribution networks, and raw material volatility (crude oil derivatives and titanium dioxide). With new corporate entrants intensifying competition, this study conducts an in-depth standalone comparative analysis covering **FY2024–25** and **FY2025–26** (incorporating FY2023–24 opening balance comparative data).

This repository contains both the **complete financial model (Excel)** and the **in-depth analytical report (PDF)**.

---

## 🏢 Companies Analyzed

| Company Name | Sector Focus & Position | Financial Model Sheet |
| :--- | :--- | :--- |
| **Asian Paints Ltd.** | Market leader; extensive decorative network & brand dominance | `Asian Paints` |
| **Berger Paints India Ltd.** | Second-largest decorative player with strong eastern India footprint | `Berger` |
| **Kansai Nerolac Paints Ltd.** | Leader in industrial/automotive coatings with expanding decorative segment | `Kansai Nerolac` |
| **JSW Paints / Dulux (AkzoNobel)** | Disruptive entrant / premium architectural coatings brand | `JSW Dulux` |
| **Indigo Paints Ltd.** | High-growth challenger known for differentiated products & tier 3/4 reach | `Indigo Paints` |

---

## 📊 Core Ratio & Financial Analysis Framework

The analysis benchmarks each company across 5 primary dimensions against the **5-Company Industry Average** (simple arithmetic mean):

```
                                  ┌─────────────────────────────┐
                                  │ Financial Statement Analysis│
                                  └──────────────┬──────────────┘
            ┌───────────────────┬────────────────┼─────────────────┬───────────────────┐
            ▼                   ▼                ▼                 ▼                   ▼
    ┌──────────────┐    ┌──────────────┐ ┌──────────────┐  ┌──────────────┐    ┌──────────────┐
    │  Liquidity   │    │ Profitability│ │   Solvency   │  │  Efficiency  │    │    Growth    │
    ├──────────────┤    ├──────────────┤ ├──────────────┤  ├──────────────┤    ├──────────────┤
    │• Current     │    │• Net Margin  │ │• Debt/Equity │  │• Materials   │    │• Revenue YoY │
    │• Quick       │    │• OPM         │ │  (excl. 116) │  │  Turnover    │    │• OPM Trend   │
    │• Cash Ratio  │    │• ROE (Avg)   │ │• Lease-Incl. │  │• Working Cap │    │• Capital Exp.│
    │              │    │• ROCE (Avg)  │ │• Int. Cover  │  │  Turnover    │    │              │
    └──────────────┘    └──────────────┘ └──────────────┘  └──────────────┘    └──────────────┘
```

### 1. Liquidity Ratios
- **Current Ratio**: Current Assets ÷ Current Liabilities
- **Quick Ratio**: (Cash & Cash Equivalents + Marketable Securities + Trade Receivables) ÷ Current Liabilities
- **Cash Ratio**: Cash & Bank Balances ÷ Current Liabilities

### 2. Profitability & Returns
- **Operating Profit Margin (OPM %)**: $[ \text{Revenue} - (\text{Total Expenses} - \text{Finance Costs}) ] \div \text{Revenue}$
- **Net Profit Margin (PAT %)**: Net Profit after Tax ÷ Revenue from Operations
- **Return on Equity (ROE)**: PAT ÷ Average Total Equity (incorporating comparative opening equity)
- **Return on Capital Employed (ROCE)**: EBIT ÷ Average Capital Employed

### 3. Solvency & Leverage
- **Debt-to-Equity (Core)**: Total Borrowings (excluding Ind AS 116 lease liabilities) ÷ Total Equity
- **Lease-Inclusive Debt-to-Equity**: (Borrowings + Total Lease Liabilities) ÷ Total Equity
- **Interest Coverage Ratio**: EBIT ÷ Finance Costs

### 4. Operating Efficiency & Turnover
- **Materials-Consumption Turnover**: Raw Materials & Stock Consumed ÷ Average Inventory (used as an accurate proxy for COGS turnover)
- **Working Capital Turnover**: Revenue from Operations ÷ Net Working Capital
- **Asset Turnover**: Revenue from Operations ÷ Average Total Assets

---

## 📁 Repository Structure

```
.
├── FAA_Financial_Statement_Analysis.xlsx   # Full financial workbook with live formulas & models
├── FAA_Financial_Statement _Analysis_Report.pdf # Comprehensive formal research & analytical report
└── README.md                               # Project documentation & overview
```

### 📑 Workbook Breakdown (`FAA_Financial_Statement_Analysis.xlsx`)
1. **Cover Page**: Project metadata, methodology guidelines, and table of contents.
2. **Company Tabs (`Berger`, `Kansai Nerolac`, `Asian Paints`, `JSW Dulux`, `Indigo Paints`)**:
   - Section A: Raw Standalone Balance Sheet & P&L Statement extractions (₹ Crore).
   - Section B–E: Categorized ratio calculations alongside industry benchmark comparison.
   - Section F: Growth rates, margin expansions, and input reference notes.
3. **Industry Summary**: Aggregated cross-sectional data, industry averages, and peer ranking tables.

### 📄 Analytical Report (`FAA_Financial_Statement _Analysis_Report.pdf`)
- Macroeconomic drivers: crude pricing trends, real estate demand, and monsoon impact.
- Qualitative commentary on supply chain resilience, dealer-network moats, and pricing power.
- Detailed comparative risk and return analysis across established leaders vs. emerging challengers.

---

## 🔍 Key Methodological Notes

- **Reporting Standard**: Figures are sourced from standalone audited financial statements under **Ind AS** (Indian Accounting Standards).
- **Lease Liability Treatment**: Debt-to-Equity is computed both **excluding** and **including** Ind AS 116 lease liabilities to isolate operating real estate leases from financial indebtedness.
- **Average Balance Convention**: Where applicable (ROE, ROCE, Turnovers), ratios utilize opening (FY23–24) and closing (FY24–25 / FY25–26) averages to prevent distortion from year-end balance spikes.
- **Materials Turnover**: Since an identical unified Cost of Goods Sold line is not uniformly disclosed across all players, *Consumption of Raw Materials, Packing Materials & Purchases* is used to maintain parity.

---

## 🚀 Getting Started & Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Ar555Rathod/PaintsFin.git
   cd PaintsFin
   ```
2. **Inspect the Financial Model**:
   Open `FAA_Financial_Statement_Analysis.xlsx` in Microsoft Excel, LibreOffice Calc, or Google Sheets to inspect the underlying dynamic formulas.
3. **Read the Comprehensive Report**:
   Open `FAA_Financial_Statement _Analysis_Report.pdf` using any PDF viewer for full strategic commentary and visual exhibits.

---

## 👤 Author

- **Arnav Rathod**
- GitHub: [@Ar555Rathod](https://github.com/Ar555Rathod)

---
*Disclaimer: This project was prepared for academic and financial analysis purposes. Financial statement data is referenced from public statutory filings.*
