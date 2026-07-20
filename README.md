# 🛒 Amazon E-Commerce Performance & Sales Analysis (2024–2026)

![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Cleaning-150458?style=for-the-badge&logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

An end-to-end data analytics portfolio project analyzing **1,000,000 Amazon e-commerce transactions**. This project covers automated data cleaning in Python and interactive business intelligence reporting in Power BI to evaluate global sales, product categories, fulfillment metrics, and discounting strategies from March 2024 through March 2026.

---

## 📌 Business Case & Objectives
The goal of this analysis is to evaluate revenue drivers, customer purchasing preferences, fulfillment efficiency, and discounting strategies to optimize business growth and operational performance.

**Key Questions Addressed:**
* Which product categories drive the majority of gross revenue and volume?
* How are customers paying for their purchases across different payment channels?
* What are the primary bottlenecks in order delivery and fulfillment?
* Does the discounting strategy directly correlate with higher category sales volume?

---

## 📈 High-Level KPI Summary

| Metric | Performance Value |
| :--- | :--- |
| **Total Revenue** | **$9.94 Billion** |
| **Total Orders** | **1,000,000 Orders** |
| **Average Price / Order** | **$9.94K** |
| **Average Customer Rating** | **3.93 / 5.00** |
| **Analysis Period** | **March 2024 – March 2026** |

---

## 📊 Dashboard Preview

> 💡 *Below is a static preview of the interactive dashboard built in Power BI.*

![Amazon Dashboard Preview](Amazon%20Dashboard.pdf)

---

## 💡 Comprehensive Business Analysis & Insights

### 1. Revenue & Category Performance
* **Electronics Dominance:** Electronics is the leading revenue driver by a massive margin, generating **$6.58 Billion** (~66% of total gross revenue).
* **Secondary Categories:** Home ranks second with **$1.53 Billion**, followed by Sports at **$1.12 Billion**. Clothing ($0.4B) and Beauty ($0.3B) represent smaller revenue shares.
* **Order Volume Balance:** Despite significant differences in total revenue, order volume across all categories is perfectly balanced at roughly **20% each** (~200,000 orders per category). The massive revenue lead for Electronics stems directly from significantly higher unit price points rather than higher sales volume.

### 2. Payment Method Distribution
* Customer payment methods are evenly split across all four supported channels with no single dominant preference:
  * **Credit Card:** 25.04%
  * **Cash on Delivery (COD):** 25.03%
  * **Debit Card:** 25.00%
  * **UPI:** 24.93%
* **Strategic Takeaway:** Payment gateway infrastructure must be maintained equally across all options. Removing or experiencing downtime on any single channel risks losing ~25% of total transactions.

### 3. Discounting Strategy
* **Electronics** receives the highest average discount rate at **40%**, which strongly supports its position as the top revenue generator.
* **Home (28%)**, **Sports (27%)**, and **Clothing (27%)** receive moderate discounting, while **Beauty (23%)** receives the lowest average discount.

### 4. Fulfillment & Operational Risks
* **Delivery Bottlenecks:** Delayed orders are a significant operational risk, standing at **29.5% (294,983 orders)**, which nearly matches the on-time Delivered rate of **29.52% (295,234 orders)**.
* **In-Transit & Returns:** 29.38% of orders (293,793) remain actively in transit, while **11.6% (115,990 orders)** resulted in returns.
* **Customer Satisfaction:** Despite delivery delays, shipping durations strictly average between **3.16 to 3.18 days**, and overall customer satisfaction ratings remain incredibly steady around **3.9 / 5.0** across all categories.

---

## 🛠️ Tech Stack & Methods Used

* **Data Cleaning & ETL:** Python (`pandas`, `numpy`)
* **Exploratory Data Analysis (EDA):** Jupyter Notebook (`.ipynb`)
* **Data Visualization & Modeling:** Power BI Desktop, DAX
* **Version Control:** Git & GitHub

---

## 📁 Repository Structure

```text
├── Amazon Analysis.pbit                  # Power BI Template File (Report layout & DAX)
├── Amazon Dashboard.pdf                  # PDF Export of report visual pages
├── Amazon_E-Commerce_Data_Cleaning.ipynb # Python Data Cleaning & ETL Notebook
├── .gitignore                            # Excludes large raw datasets from repo
└── README.md                             # Documentation & Analysis Summary
