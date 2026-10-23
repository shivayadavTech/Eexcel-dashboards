# Blinkit Sales Performance Dashboard (Excel, Power Query & VBA)

## Project Overview
This project presents an interactive Business Intelligence Sales Dashboard developed for Blinkit (Quick Commerce grocery delivery). It provides end-to-end performance tracking across retail dark stores, product categories, geographic tiers, and customer ordering trends.

The raw dataset was cleansed and transformed using **Power Query**, modeled through dynamic **Pivot Tables & Summary Matrices**, and designed into an executive-grade dashboard automated with **Excel VBA & Macros**.

---

## Dashboard Preview
![Blinkit Sales Dashboard Preview](blinkit_dashboard_preview.png)

---

## Core Executive KPIs
Key business metrics calculated across the entire retail distribution network:
* **Total Sales:** **$1.20M** (Total Network Revenue)
* **Average Sales:** **$141** (Average Basket Value per Order)
* **Number of Items:** **8,536** (Total Product SKUs / Records Tracked)
* **Average Rating:** **3.92 / 5.0** (Customer Satisfaction Index)

---

## Business Insights & Visual Analytics

### 1. Item Fat Content Breakdown (Donut Chart)
* **Low Fat Products:** **65%** market share ($777.4k revenue).
* **Regular Products:** **35%** market share ($426.0k revenue).
* **Business Takeaway:** Health-conscious and low-fat grocery items significantly dominate customer basket volume in quick commerce.

### 2. Category Performance (Horizontal Bar Chart)
* **Top Drivers:** **Fruits & Vegetables ($178.3k)** and **Snack Foods ($176.2k)** contribute approximately 30% of total platform sales.
* **Core Grocery:** Household ($136.0k), Frozen Foods ($118.6k), and Dairy ($101.4k) demonstrate stable recurring demand.
* **Niche Segments:** Seafood ($9.1k) and Breakfast items ($15.6k) remain low-volume categories.

### 3. Regional Tier Performance
* **Tier 3 Outlets:** Highest revenue generator (**$473.8k**), driven by high demand for both Low Fat ($307.8k) and Regular ($166.0k) goods.
* **Tier 2 Outlets:** Strong second place (**$393.2k**).
* **Tier 1 Outlets:** Generated **$336.4k**.

### 4. Outlet Format & Size Efficiency
* **Medium Outlets:** Highest contributing format at **42%** ($509.6k) revenue share.
* **Small Outlets:** Contributed **37%** ($444.8k).
* **High Outlets:** Contributed **21%** ($249.0k).
* **Supermarket Type 1:** The operational backbone channel, handling **$787.5k** revenue across 5,577 items.

### 5. Historical Growth Trend
* Establishment timeline shows steady revenue scaling from 2011 ($78.1k) to a peak in 2018 (**$206.2k**).

---

## Technical Architecture & Pipeline

### 1. Data Cleaning & ETL (Power Query)
* **Text & Category Standardization:** Unified inconsistent labels in raw data (e.g., merging `LF`, `low fat`, and `Low Fat` into standard `Low Fat` vs `Regular`).
* **Missing Value Imputation:** Handled missing values and blank rows within the `Item Weight` field.
* **Data Formatting:** Standardized outlet naming conventions, formatted currencies, percentages, and numeric types.

### 2. Data Modeling & Separation of Concerns
The workbook is built across 4 distinct functional layers:
* `Raw Data`: Untouched source dataset.
* `Clean data`: Production-ready transformed table output from Power Query.
* `Pivot & KPI`: Analytical backend engine containing Pivot Tables and calculated KPI matrices.
* `Dashboard`: Front-end visualization interface optimized for user interaction.

### 3. Excel VBA & Automation
* **Custom Navigation Bar:** Floating buttons on sheets for seamless switching between Dashboard, Analysis, and Data views.
* **Interactive Slicers:** Dynamic cross-filtering by Outlet Size, Location Type, and Item Type.
* **Filter Reset & Refresh Automation:** One-click reset macro to clear active slicers and synchronize pivot caches.

---

## Repository Files
* `Blinkit_Grocery_Data.xlsm` — Macro-enabled interactive Excel workbook.
* `Raw_Grocery_Data.csv` — Raw, uncleaned source dataset.
* `blinkit_dashboard_preview.png` — High-resolution preview image of the dashboard.
* `README.md` — Project documentation and business breakdown.

---

## How to Use
1. Download `Blinkit_Grocery_Data.xlsm` from this repository.
2. Open the file in Microsoft Excel and select **Enable Content / Macros** when prompted.
3. Use the left-side slicers to dynamically filter data across regions, outlet sizes, and item categories.
4. Use the navigation buttons on the interface to explore the underlying calculations and data sheets.

---

## Author & Freelance Services
**Shivanand Yadav**  
*Front-End Developer | Excel Automation & Dashboard Specialist*

* **Fiverr:** [fiverr.com/shivanandyadav](https://www.fiverr.com)
* **Freelancer:** [freelancer.com/u/shivanandyadav](https://www.freelancer.com)
* **LinkedIn:** [Shivanand Yadav LinkedIn Profile](https://www.linkedin.com/in/shivanandyadav1/)
* **GitHub:** [shivayadavTech GitHub Profile](https://github.com/shivayadavTech)

  
