# ☕ Café Sales & Operations Analytics Dashboard

An end-to-end data analytics project transforming raw retail transactions into actionable business intelligence using Python and Power BI.



---

## 📌 Problem Statement
Independent food and beverage retail businesses often struggle to track holistic operational performance due to fragmented data across multiple transactions, varying payment channels, and diverse dining preferences. Management needed a centralized solution to monitor overall business performance, evaluate item-level profitability across **10,000 retail transactions ($89.19K in total sales)**, and uncover operational bottlenecks during peak hours.

---

## 🛠️ End-to-End Process

### 1. Data Preparation & Cleaning (Python)
* Handled missing values and standardized text categorical columns (item names, payment methods).
* Formatted raw date fields into proper datetime objects to support chronological aggregation.
* Validated numeric attributes (*Price Per Unit*, *Quantity*, *Total Sales*) for precise metric calculations.

### 2. Data Modeling & Visualization (Power BI)
* Developed a custom **"Warm Café" aesthetic** featuring espresso browns (`#2C1D11`), creams, and warm caramels.
* Used the "Sort by Column" feature to ensure months sorted chronologically (January to December).
* Built a clean layout incorporating high-level KPI cards, temporal trends, category breakdowns, and operational charts.

---

## 📊 Key Insights & Analytical Findings

* **Top Sellers:** "Eatables" lead overall sales, with **Salads** standing out as the single highest revenue-generating item on the menu.
* **Payment Trends:** Customers heavily favor digital/online payment methods over cash, highlighting a strong shift toward cashless transactions.
* **Traffic Patterns:** Weekend traffic spikes significantly on **Saturdays and Sundays** (crossing over $500 blocks), while weekdays maintain a steady, moderate baseline.
* **Seasonal Dips:** **February** records the lowest sales of the year, signaling a clear opportunity for targeted seasonal promotions.

---

## ⚠️ Operational Findings ("Unspecified" Data Analysis)
* **The Issue:** A high volume of transactions lacked specific logging for payment channels and dining options, recorded as "Unspecified."
* **Root Cause:** Diagnosed as a rush-hour bottleneck where cashiers intentionally skipped optional POS fields to keep checkout lines moving.
* **Impact:** Preserves speed at the register, but creates a blind spot for management tracking exact customer segmentation.

---

