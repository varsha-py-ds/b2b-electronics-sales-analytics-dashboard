# 📊 Sales MTD & YTD Executive Analysis Dashboard

An interactive executive analytics dashboard built to track **Month-to-Date (MTD)** and **Year-to-Date (YTD)** sales performance, YoY growth, branch contributions, top-performing smartphone/laptop SKUs, and buyer concentration across **FY 2026–27** (cutoff: 23 Oct).

---

## 📌 Overview

The report is organized into three interactive views with global **YTD (Apr–Oct)** and **MTD (Oct)** period toggles:

| Page / View | What It Shows |
| :--- | :--- |
| **Overview** | Executive KPI cards with sparklines & YoY deltas, Sales by FY comparison, Branch contribution donut, Monthly CY vs. PY trend (Sales / Qty / Orders), Top Models, and Top Buyers |
| **Branches & Buyers** | Side-by-side YTD vs. Oct MTD branch comparison chart, branch highlight cards, and a searchable Party-Wise Executive Comparison table (`Buyer 01`–`Buyer 10`) with PY/CY Qty, Sales, and YoY Growth % |
| **Models & Comparison** | Complete SKU-wise executive matrix ranking top models (`iPhone 17`, `iPhone 16`, `iPhone 15`, `MacBook`) with Last Year vs. Current Year Qty & Sales, Revenue Share %, and YoY Growth % |

---

## 📸 Screenshots

### Overview — YTD (Apr–Oct)
![Overview YTD](images/overview_ytd.png)

### Overview — MTD (Oct)
![Overview MTD](images/overview_mtd.png)

### Branches & Buyers
![Branches and Buyers](images/branches_buyers.png)

### Models & Comparison
![Models and Comparison](images/models_comparison.png)

---

## ✨ Features

* **Executive KPI Cards with Sparklines:** Tracks Gross Sales, Net Basic Sales, Average Ticket Size, Total Quantity, and Total Invoices alongside Current Year (CY) vs. Prior Year (PY) comparisons and percentage deltas.
* **Global & Visual-Level Period Toggles:** Instant switching between **YTD (Apr–Oct)** and **MTD (Oct)** at the report level, plus local toggles on individual cards (`Sales / Qty / Orders` and `YTD / MTD`).
* **Multi-Year & YoY Trend Analysis:** Compares `FY 25–26`, `FY 24–25`, `FY 26–27`, and `LYTD 25–26`, paired with a monthly CY vs. PY curve (solid vs. dashed line) and interactive hover tooltips.
* **Granular Drill-Down Tables & Search:** Includes a buyer filter (`Filter buyer...`), SKU search (`Search SKU...`), color-coded YoY growth badges, and a one-click **PDF** export option.
* **Data Privacy & Anonymization:** Client/party names are masked (`Buyer 01`–`Buyer 10`) and company branding is removed for portfolio demonstration.

---

## 🔍 Key Insights

* **YTD Top-Line Growth:** YTD Gross Sales reached **₹233.29 Cr** (+2.3% YoY vs. ₹228.02 Cr LYTD) across **34,257 Pcs** and **466 Orders** (+14.2% YoY in invoice volume).
* **October MTD Snapshot:** October MTD recorded **₹15.67 Cr** in Gross Sales across **2,067 Pcs** (25 Orders), with Average Ticket Size rising **+22.4% YoY** to **₹62.69 L** (up from ₹51.22 L).
* **Regional & Branch Mix:** **Karnataka** leads YTD revenue at **₹90.3 Cr (38.7% share)**, closely followed by **Gujarat** at **₹88.3 Cr (37.9%)** and **Gujarat Pvt** at **₹45.4 Cr (19.4%)**, with Gujarat Pvt driving 100% of October MTD activity (₹15.7 Cr).
* **Product & SKU Performance:** **iPhone 17 8/256GB** leads YTD sales at **₹74.24 Cr (31.8% share)**, followed by **iPhone 16 8/128GB** (**₹55.26 Cr / 23.7%**) and **iPhone 15 6/128GB** (**₹31.88 Cr / 13.7%**), while iPhone 16 8/128GB leads Oct MTD at ₹4.35 Cr.
* **Buyer Concentration:** **Buyer 01** leads YTD revenue at **₹55.78 Cr** (7,069 Pcs, +452.2% YoY), while **Buyer 06** leads Oct MTD performance at **₹6.91 Cr** (1,009 Pcs).

---

## 🛠️ Tech Stack

| Area | Tools |
| :--- | :--- |
| **BI & Visualization** | Interactive Dashboard Design, Executive KPI Modeling & Reporting |
| **Data Modeling & Logic** | Time-Intelligence Calculations (MTD, YTD, LYTD, YoY Growth %), Variance Analysis |
| **Data Source** | Anonymized B2B Electronics Sales Dataset (Excel / CSV) |

---

## 📂 Project Structure

```text
sales-mtd-ytd-executive-analysis/
├── images/
│   ├── overview_ytd.png
│   ├── overview_mtd.png
│   ├── branches_buyers.png
│   └── models_comparison.png
└── README.md
