# 📊 MIS Reporting & Commercial Analytics Dashboards

Interactive operational dashboards built in Microsoft Excel to track revenue performance, fulfillment margins, warehouse utilization, and SKU replenishment cycles.

---

## 🛒 1. Amazon Commercial Performance Dashboard
**Domain:** E-Commerce Revenue Analysis & Channel Margin Diagnostics

* **Commercial Scale:** Monitored **₹3,604,795** in gross sales, **₹1,215,011** net profit (**33.76%** margin), and 1,686 total units sold across 300 orders.
* **Channel Distribution:** Evaluated performance by fulfillment type (FBA vs. FBM), state-level order density, and ad spend efficiency.
* **Return & Leakage Control:** Analyzed 91 returned units across 34 orders to identify margin leakage and flag high-return product lines.

![Amazon Seller Dashboard](Amazon%20Seller%20Dashboard.png)

*Working Spreadsheet:* [`Amazon_Seller_Data.xlsx`](Amazon_Seller_Data.xlsx)

---

## 📦 2. Warehouse & Inventory Operations Dashboard
**Domain:** Stock Visibility, Reorder Tracking & Carrying Valuation

* **Inventory Scale:** Managed **34,580 stock units** across **300 SKUs** representing an aggregate carrying value of **₹35,126,959**.
* **Regional Logistics:** Tracked regional warehouse capacity and inventory distribution across Pune, Mumbai, Hyderabad, Delhi, and Bangalore hubs.
* **Stock Risk Alerts:** Flagged 121 low-stock items and 16 out-of-stock items below reorder thresholds to prevent dispatch bottlenecks.

![Inventory Management Dashboard](Inventory%20Management%20Dashboard.png)

*Working Spreadsheet:* [Inventory Management.xlsx](Inventory%20Management.xlsx)

---

## 📊 3. Executive Sales & Cash Realization Dashboard
**Domain:** Operational Revenue Diagnostics & Receivables Audit

* **Commercial Scale:** Monitored **₹22.3M** in gross revenue across 5 regions with a **35.0%** profit margin.
* **Collections Diagnostics:** Tracked **₹19.5M** cash realized against **₹980.8K** in at-risk overdue receivables.
* **Audit Ledger:** Granular customer payment tracking across regional distribution channels.

🔗 **[Open Interactive Live Mobile Dashboard](https://datastudio.google.com/s/g0x91yhg68Y)**

---

### 📊 4. Executive Summary & Profitability Dashboard

**Domain:** Multi-Channel Sales Performance & Margin Diagnostics

* **Commercial Scale:** Monitored **$645.2K** in gross revenue across 2,707 orders with a **45.94%** profit margin ($296.4K total profit).
* **Geographic Distribution:** Tracked top European markets including Spain, Austria, Czechia, Belgium, and France alongside regional European performance.
* **Channel & Margin Analytics:** Granular visibility across Online Store, Marketplace, Corporate, and Retail Partner channels.
* **Working Spreadsheet:** [Excel Sales Dashboard.xlsx](Excel%20Sales%20Dashboard.xlsx)

---

## 📊 Sales & Inventory Management MIS Dashboard (Power Query & Power Pivot)

An end-to-end Management Information System (MIS) and Business Intelligence reporting solution built in **Microsoft Excel** for **Eastern Industrial Supplies Pvt. Ltd.** (a B2B industrial distributor).

### Key Features & Technical Implementation
* **ETL & Data Modeling:** Cleaned and structured four relational tables (`Sales`, `Products`, `Customers`, `Inventory`) via **Power Query** and modeled a **Star Schema** in **Power Pivot**.
* **DAX Measures:** Created custom measures for `Total Revenue`, `Total COGS`, `Gross Profit`, `Gross Margin %`, `Closing Stock`, and `Stock Deficit`.
* **Interactive BI Dashboard (`DASHBOARD`):** Built 6 dynamic KPI cards, 6 PivotCharts (Monthly Revenue Trend, Top 10 Products, Stock vs. Deficit by Category, Payment Status Donut, State Revenue Bar, and Category Revenue vs. Profit), and cross-connected **Slicers**.
* **Formula-Driven Control Sheet (`OVERVIEW`):** Engineered an operational monitor using `SUMPRODUCT`, `XLOOKUP`, Data Validation dropdowns, and Conditional Formatting for low-stock alerts.

### Dashboard Previews
![Sales & Inventory BI Dashboard](https://github.com/pratikdey360/Mis-reporting-Dashboard/blob/main/SALES%20%26%20INVENTORY%20ANALYSIS%20DASHBOARD.xlsx)

