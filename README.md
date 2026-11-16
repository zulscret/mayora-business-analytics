# 🍪 PT Mayora Indah Tbk (IDX: MYOR) — Integrated Corporate Business & Financial Analytics
> **Comprehensive FMCG Equity & Operations Research: Global Export Moat, Commodity Price Sensitivity, Route-to-Market Distribution Architecture, and BCG Portfolio Dynamics**

[![Author](https://img.shields.io/badge/Author-Muhammad%20Zulvan%20Yahya-1E3A8A?style=flat&logo=github)](https://github.com/zulscret)
[![Company](https://img.shields.io/badge/Ticker-IDX%3A%20MYOR-B45309?style=flat)](#)
[![Industry](https://img.shields.io/badge/Sector-Consumer%20Staples%20%2F%20FMCG-059669?style=flat)](#)
[![Stack](https://img.shields.io/badge/Stack-Python%20%7C%20Excel%20Financial%20Modeling%20%7C%20BCG%20Matrix-2563EB?style=flat)](#)

---

## 📌 Executive Summary
**PT Mayora Indah Tbk (IDX: MYOR)** is one of Southeast Asia's foremost branded food and beverage conglomerates. Unlike typical domestic-bound Indonesian consumer staples peers, Mayora has successfully built a **world-class global export engine**, generating over **44.0% of net revenue from &gt;100 international destination countries** (notably leading the instant coffee category in the Philippines with *Kopiko*).

This repository presents an institutional-grade business and financial performance case study spanning **FY2020 through FY2025E**, diagnosing:
1. **Commercial Growth & Export Power:** 5-year Net Revenue CAGR of **10.1%**, scaling from Rp 24.5 Trillion (2020) to Rp 39.65 Trillion (2025E).
2. **Gross Margin Resilience Against Global Commodity Cycles:** Analysis of how Mayora navigated the 2021–2022 global raw material inflation shock (wheat, coffee, sugar, packaging) and successfully expanded Gross Profit Margin back to **27.0%** in 2024–2025.
3. **Route-to-Market (RTM) Distribution Moat:** The strategic role of exclusive distributor **PT Inbisco Niagatama Semesta** across 1.5M+ General Trade (GT) warungs and centralized Modern Trade (MT) channels.
4. **Dynamic Strategic Modeling:** BCG Growth-Share Matrix classification and a live **Commodity Price Sensitivity Simulator** in Microsoft Excel.

---

## 🏗️ Repository Architecture
```text
mayora-business-analytics/
├── data/
│   ├── myor_financials_5yr.csv             # 5-Year audited Income Statement, Balance Sheet & Margins
│   ├── myor_category_breakdown.csv         # Food vs Beverages divisional contribution
│   ├── myor_commodity_exposure.csv         # COGS raw material basket weighting & market exposures
│   └── myor_geographic_sales.csv           # Domestic vs International sales breakdown
├── excel/
│   └── MYOR_Corporate_Valuation_and_Financial_Model.xlsx # Dynamic financial model with live formulas
├── charts/
│   ├── myor_revenue_growth_export_domestic.png # Domestic vs Export revenue stack + % export share
│   ├── myor_profitability_margins_trend.png    # Gross, Operating, and Net Margin cycle evolution
│   ├── myor_cogs_commodity_breakdown.png       # Raw material cost basket donut chart
│   └── myor_bcg_matrix_portfolio.png           # 2x2 BCG Growth-Share Matrix of flagship brands
├── reports/
│   ├── Mayora_MYOR_Integrated_Business_Case_Study.pdf  # Executive 2-page institutional research paper
│   └── Mayora_MYOR_Integrated_Business_Case_Study.html # Clean HTML source template
├── build_mayora_analytics.py               # Automated data, chart & modeling pipeline
└── README.md                               # Project documentation
```

---

## 📊 Key Analytical Dimensions

### 1. 5-Year Financial Performance Snapshot
| Metric (Billion IDR) | FY2020 | FY2021 | FY2022 | FY2023 | FY2024 | FY2025E | 5-Yr CAGR |
|---|---|---|---|---|---|---|---|
| **Domestic Net Sales** | 14,382 | 16,124 | 17,758 | 17,621 | 20,072 | 22,204 | **+9.1%** |
| **Export Net Sales** | 10,095 | 11,782 | 12,911 | 13,864 | 15,770 | 17,446 | **+11.6%** |
| **Total Net Sales** | **24,477** | **27,906** | **30,669** | **31,485** | **35,842** | **39,650** | **+10.1%** |
| **Gross Profit** | 7,187 | 6,928 | 6,881 | 8,349 | 9,606 | 10,705 | **+8.3%** |
| **Net Profit (PAT)** | 2,061 | 1,188 | 1,941 | 3,194 | 3,422 | 3,886 | **+13.5%** |
| **Gross Margin (%)** | 29.4% | 24.8% | 22.4% | 26.5% | 26.8% | **27.0%** | -240 bps |
| **Net Margin (%)** | 8.4% | 4.3% | 6.3% | 10.1% | 9.5% | **9.8%** | +140 bps |
| **Return on Equity (ROE)** | 18.3% | 10.5% | 15.1% | 21.0% | 19.7% | **19.6%** | High Quality |

---

### 2. BCG Growth-Share Portfolio Matrix
* **Cash Cows:** *Roma Kelapa & Marie Gold, Beng-Beng, Torabika Cappuccino, Energen*. Dominant market share in mature, stable FMCG categories providing massive cash flow generation.
* **Stars:** *Kopiko Global Export* (double-digit growth across Asia & Middle East) and *Teh Pucuk Harum & Le Minerale* (rapidly gaining volume share in RTD beverages).
* **Question Marks:** *Kopiko Lucky Day (RTD Coffee)* and single-origin specialty blends testing premium cold-chain segments.
* **Dogs / Niche:** *Bakmi Mewah & Mie Gelas* maintained as tactical shelf-presence products.

---

### 3. Raw Material Basket & Price Sensitivity
Raw materials represent **82.5% of Cost of Goods Sold (COGS)**:
* **Refined Sugar (22.0%):** Tied to domestic industrial quotas and international raw sugar prices.
* **Wheat Flour (20.5%):** Directly exposed to global CBOT milling wheat futures.
* **Robusta Coffee Beans (18.5%):** Sourced from Sumatra & Java; sensitive to climate and El Niño crop yields.
* **Palm Oil & Specialty Fats (13.0%):** Governed by Indonesian DMO regulations.
* **Packaging Film, PET & Cartons (15.0%):** Linked to petrochemical resin and pulp price indices.

A **$\pm 10\%$ shock across primary commodities** alters Mayora's annual Gross Profit by approximately **Rp 1.76 Triliun** ($\pm 165\text{ bps}$ on Gross Margin). Mitigation is achieved through 3–6 month forward procurement contracts and tactical pack-size/grammage engineering.

---

## 📈 Supply Chain & Working Capital Benchmark
* **Cash Conversion Cycle (CCC):** Managed efficiently at **88 days** (Days Sales Outstanding: 58 days, Days of Inventory: 64 days, Days Payable: 34 days).
* **Route-to-Market Moat:** Exclusive downstream execution by **PT Inbisco Niagatama Semesta** ensures rapid market penetration into traditional warungs with high-velocity single-serve sachets (Rp 1,000 – Rp 2,000 price points).

---

## 👨‍💻 Author
**Muhammad Zulvan Yahya**  
*S1 Information Systems — Universitas Pembangunan Nasional "Veteran" Jakarta*  
*Specialization: Corporate Financial Modeling, FMCG Operations, Business Analytics, SQL & Python*
