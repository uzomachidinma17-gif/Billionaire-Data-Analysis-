# Billionaire Statistics Data Analysis (Excel Portfolio Project)
A comprehensive data analysis project exploring global wealth concentration, industry trends, and age-velocity metrics. This project blends classic executive reporting with advanced metric engineering across a 476-entity cohort.

## 📊 Core Sheets & Project Architecture

### 1. Global Wealth Distribution Dashboard
* **Structure**: PivotTable analyzing cumulative net worth by country.
* **Visualization**: Custom Chart displaying the **Percentage of Grand Total Wealth**, filtered to isolate the **Top 10 Countries** for optimized scannability.

### 2. Sector Performance & Regional Dynamics
* **Structure**: PivotTable cross-referencing industry categories against wealth origins.
* **Interactive Filtering**: Linked **Country Slicer** allowing users to dynamically filter and inspect how dominant industries shift across different global regions.

### 3. Demographic Distribution
* **Structure**: Statistical age bucketing (grouped intervals) mapped against the **Average Final Worth** to isolate the definitive lifecycle "sweet spot" for wealth retention.

### 4. The Wealth Velocity Anomaly (Advanced Feature Engineering)
* **Structure**: PivotTable displaying the **Average Wealth Velocity** (`[finalWorth] / [age]`) across sectors.
* **Visualization & Finding**: Custom chart explicitly highlighting **Automotive** as the #1 fastest wealth generator per year of life, exposing a major structural anomaly over Technology or Finance.

### 5. Cumulative Distribution & Pareto Analysis
* **Structure**: Main table calculated running totals to evaluate the Pareto Principle.
* **Finding**: Identified an **80/54 wealth split** across the 476 records, mathematically proving a more localized distribution of capital compared to standard multi-thousand-row global datasets.

---

## 🛠️ Tools & Technical Competencies Used
* **Microsoft Excel**: Feature Engineering, PivotTables, Slicers, Data Sorting/Filtering, Custom Value Summarization (Averages, Sums, % of Grand Total), Categorical Age Grouping.
* **Data Cleansing**: Uniform formatting of data fields and tables across 476 records.
* **Data Storytelling**: Strategic dashboard layout design and custom accent formatting to highlight primary insights for business intelligence.

---

## 📁 Repository Structure
* `Billionaire_Statistics_Dataset.xlsx` - Full Excel workbook featuring all formulas, engineered columns, PivotTables, and Charts.
* `README.md` - Technical documentation and analytical summaries.
