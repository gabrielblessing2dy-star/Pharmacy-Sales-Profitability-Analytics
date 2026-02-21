# Pharmacy Sales & Profitability Analytics – Onyx Data Challenge
<p align="center">
  <a href="https://app.powerbi.com/view?r=eyJrIjoiY2E4MGE5NzAtNzExZC00ODM5LWFhNDQtMzkzNjFjNjc2ZmNiIiwidCI6ImNjYjk2MDQwLTZmZTMtNDJmNi05ZjgwLWM2ZTA0ZjJkYjBmYyJ9">
    <img src="https://img.shields.io/badge/View%20Live%20Dashboard-Power%20BI-yellow?style=for-the-badge&logo=powerbi" />
  </a>
</p>

##  Project Overview

This project analyzes transactional data from a European pharmacy distributor operating across **8 countries** and **120 store locations**.

Developed as part of the **Onyx Data #DataDNA Challenge (Jan–Feb 2026)**, the dashboard transforms fragmented regional data into a centralized performance intelligence system.

The objective: enable leadership to optimize international operations, uncover margin erosion, and shift from revenue-focused reporting to profit-first decision-making.

---

##  Problem Statement

Despite **4.4% revenue growth**, overall corporate margin remains stagnant at **28.11%**.

The core issue is a visibility gap:

- Revenue growth masks operational inefficiencies  
- Fragmented country-level reporting limits transparency  
- Pharmacy formats (Urban, Suburban, Rural) perform inconsistently  
- High-volume “loss leaders” distort perceived performance  

Without structured drill-down analysis, leadership cannot clearly distinguish true profit drivers from margin eroders.

---

##  Executive Summary

This project delivers a comprehensive profitability analysis across Executive, Geographic, and Product dimensions.

By integrating performance data across 228K+ units generating **$4.4M in revenue**, the solution identifies critical margin leaks and highlights optimization opportunities at regional and product levels.

The dashboard moves reporting beyond “How much did we sell?” to “How much did we keep?”

---

##  Business Questions Answered

1. **Performance Visibility**  
   Which countries and regions outperform or underperform the 28% margin benchmark?

2. **The Volume–Margin Paradox**  
   Which high-volume products are eroding overall profitability?

3. **Geographic Patterns**  
   How do margin and revenue trends vary across the 8 countries?

4. **Pharmacy Format Dynamics**  
   What structural differences exist between Urban, Suburban, and Rural locations?

5. **Seasonality & Promotions**  
   How do seasonal fluctuations and discounting strategies impact margin protection?

6. **Operational Accountability**  
   Can executives drill from global country-level metrics to individual pharmacy-level outliers?

---

## 🛠 Tools & Methodology

### Tools Used

- **Power BI**  
  Designed and developed a multi-page interactive dashboard with relational modeling.

- **DAX (Data Analysis Expressions)**  
  Engineered custom measures including:
  - YoY growth metrics  
  - Weighted margin calculations  
  - Contribution analysis  
  - Dynamic “At-Risk” product flags  

---

##  Methodology

### 1️⃣ Dual-Quadrant Stratification

- **Revenue vs. Profitability**  
  Segmented 120 pharmacies to identify high-revenue locations failing to meet margin targets.

- **Quantity Sold vs. Profit Margin**  
  Categorized 220+ products into:
  - **Volume Leaders** (High Sales / Low Margin)  
  - **Stars** (High Sales / High Margin)  

---

### 2️⃣ Risk-Based Auditing Framework

Built a **Conditional Health Status System**:

- 🔴 Red → Below 28% corporate margin benchmark  
- ⚪ Grey → Meeting or exceeding benchmark  

This system automatically flags underperforming brands, regions, and categories to support profit-first decisions.

---


##  Dashboard Preview

### 1️⃣ Executive Performance Overview
<img src="Executive%20page.jpg" width="1000">

High-level benchmarking of revenue vs. margin, including real-time risk indicators.

---

### 2️⃣ Geographic & Pharmacy Analysis
<img src="Geography%20dashboard.jpg" width="1000">

Country-level and pharmacy-format performance comparison across Urban, Suburban, and Rural locations.

---

### 3️⃣ Product & Margin Intelligence
<img src="Product%20page.jpg" width="1000">

Product hierarchy analysis identifying volume leaders, margin dilution risks, and portfolio gaps.

---

## Key Insights

| Operational Challenge | Data Insight | Strategic Direction |
|-----------------------|--------------|---------------------|
| Fragmented Visibility | Revenue growing at 4.4% while costs rise at 4.2%, tightening profit expansion | Centralized KPIs to monitor Cost-to-Revenue ratio |
| High-Volume, Low-Margin Distortion | Prescription category at 21.98% margin vs 28.11% benchmark | Strict cost controls on volume drivers |
| Pharmacy Type Variance | Urban pharmacies generate 76.2% of total profit but are highly discount-sensitive | Protect Urban margins while expanding Rural footprint |
| Regional Underperformance | France, Spain, Netherlands flagged as “Red” zones | Drill-down audits to identify regulatory or supply chain bottlenecks |
| Portfolio Health Risks | 76 products (~33%) underperform; AntiBioX at 21.3% margin | Portfolio pruning strategy |
| Promotional Inefficiency | Flat 0.20 Promo Margin indicates blanket discounting | Shift to tiered, category-specific promotions |

---

##  Recommendations

### A. Portfolio Optimization ("Trim the Tail")

Review 76 underperforming SKUs.  
Remove products below 25% margin threshold and reallocate shelf space toward high-margin categories:

- Wellness (33.68%)  
- Personal Care (33.47%)

---

### B. Regional Margin Recovery

Conduct deep-dive investigations into Netherlands and France operations.

Align pricing toward the $19.40 average benchmark and assess COGS or competitive pricing pressures.

---

### C. Promotion Reform

Replace blanket discounting with a **Tiered Promotional Model**:

- Protect high-volume Prescription margins  
- Use aggressive promotions selectively for high-margin attachments  

---

### D. Urban Channel Protection

Audit pricing structures in Urban pharmacies.

Even a 1% margin improvement in this primary profit engine significantly impacts total corporate profitability.

---

## Technical Implementation

- Integrated fragmented ERP extracts into a unified analytics model  
- Applied Quadrant Analysis to separate “Stars” from “Dogs”  
- Enabled two-click Country → Pharmacy drill-down accountability  
- Automated margin benchmarking across all hierarchy levels  

---

##  Business Impact

This solution transforms reporting from revenue-focused dashboards into a profit-first intelligence system.

By combining structured data modeling, quadrant analysis, and drill-down accountability, the project enables leadership to:

- Detect margin erosion early  
- Rationalize underperforming SKUs  
- Protect high-performing regions  
- Align promotions with profitability strategy  

The result: scalable analytics aligned with strategic growth and margin protection.
