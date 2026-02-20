# Pharmacy Sales & Profitability Analytics – Onyx Data Challenge

## 📊 Project Overview

This project analyzes transactional data from a European pharmacy distributor operating across **8 countries** and **120 store locations**.

Developed as part of the **Onyx Data #DataDNA Challenge (Jan–Feb 2026)**, the dashboard transforms fragmented sales data into a centralized performance intelligence system.  

The goal: enable leadership to optimize international operations, identify margin erosion, and protect profitability.

---

## 🚩 Problem Statement

Despite a **4.4% revenue growth**, overall margins remain stagnant at **28.11%**.

The core issue is a visibility gap:
- Revenue growth masks operational inefficiencies  
- Fragmented country-level reporting limits transparency  
- Pharmacy formats (Urban, Suburban, Rural) perform inconsistently  
- High-volume “loss leaders” distort performance perception  

Without drill-down clarity, leadership cannot confidently distinguish true profit drivers from margin eroders.

---

## 🔍 Business Questions Answered

1. **Performance Visibility**  
   Which countries and regions are outperforming or underperforming the 28% margin benchmark?

2. **The Volume–Margin Paradox**  
   Which high-volume products are reducing overall profitability?

3. **Geographic Performance Patterns**  
   How do sales and margin trends vary across the 8 countries, and where are hidden regional opportunities?

4. **Pharmacy Format Dynamics**  
   What performance differences exist between Urban, Suburban, and Rural locations?

5. **Seasonality & Promotions**  
   How do seasonal demand fluctuations impact revenue and margin? Are current discount strategies justified?

6. **Operational Accountability**  
   Can leadership drill from country-level summaries down to individual pharmacy outliers for targeted optimization?
## Tools & Methodology

### Tools Used

- **Power BI**  
  Designed and developed an interactive, multi-page dashboard with relational data modeling (star schema).

- **DAX (Data Analysis Expressions)**  
  Engineered custom YoY growth metrics, weighted margin calculations, and dynamic "At-Risk" flags to identify margin erosion.

  ## 🧠 Methodology

### 1️⃣ Dual-Quadrant Stratification

- **Revenue vs. Profitability**  
  Segmented 120 pharmacies to identify high-revenue locations failing to meet margin targets.

- **Quantity Sold vs. Profit Margin**  
  Categorized 220+ products to separate:
  - **Volume Leaders** (High Sales / Low Margin)
  - **Stars** (High Sales / High Margin)

---

### 2️⃣ Data Modeling

- Designed a **Star Schema** connecting:
  - Geography
  - Product Hierarchy (Category → Brand → Product → Pack Size)
  - Pharmacy Format (Urban, Suburban, Rural)

- Enabled high-performance filtering and scalable drill-down analysis.

---

### 3️⃣ Risk-Based Auditing Framework

- Built a **Conditional Health Status System**:
  - 🔴 Red → Below 28% corporate margin benchmark  
  - ⚪ Grey → Meeting or exceeding benchmark  

- Automatically flags underperforming categories and brands to support profit-first decision-making.

  ## 📊 Dashboard Preview

![Dashboard Overview](assets/dashboard-overview.png)
   
   
   

   
