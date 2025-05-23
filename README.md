# 📊 Electronics Sales Dashboard (Power BI)

## 🔍 Overview

This project showcases an **interactive Power BI dashboard** developed to analyze annual electronics sales across buyer segments, regions, product lines, and discount bands. It emphasizes profitability, performance disparities among buyer types, sales seasonality, and product-level insights to inform strategic decisions.

The dashboard delivers visually intuitive insights, including:

* Gross vs. Net Sales Analysis
* Monthly Sales Trends
* Country-Wise Sales Contributions
* Discount Impact on ROI
* Buyer Segment & Product-Level Profitability

---

## 📁 Repository Contents

| File Name                | Description                                              |
| ------------------------ | -------------------------------------------------------- |
| `Sales_Dashboard.pbix`       | Power BI dashboard with all visuals and filters  |
| `Dashboard_Insights.pdf`     | Key business insights derived from the dashboard |
| `dashboard_screenshots/`     | Screenshots of dashboard views         |
| `electronics_sales_data.csv` | Raw dataset used to build the dashboard          |
| `README.md`                  | Documentation for this Power BI project          |

---

## 🎯 Objectives

* Evaluate **gross vs. net sales** to assess discount impacts.
* Identify **high and low ROI buyer segments**.
* Analyze **country-wise sales concentration**.
* Investigate **sales and profit trends over months**.
* Measure the **ROI impact of varying discount bands**.
* Uncover **top-performing products** and improvement areas.
* Provide **strategic recommendations** to optimize profitability.

---

## 🛠️ Tools Used

* **Power BI Desktop**
* **Power Query (ETL operations)**
* **Microsoft Excel (data cleaning/preprocessing)**

---

## ✅ Step-by-Step Procedure

### 🔹 Step 1: Data Import & Preparation

* Imported cleaned sales data including metrics like gross/net sales, discount bands, buyer types, product names, countries, months.
* Verified and transformed columns using Power Query:

  * Data types corrected
  * Null/missing values removed
  * Custom columns added (e.g., ROI, Profit, Year-Month)
  * Categorized buyer types and grouped discount bands

### 🔹 Step 2: Dashboard Development in Power BI

* **Visualizations Used**:

  * **KPI Cards**: Gross Sales, Net Sales, Profit, ROI
  * **Line & Area Charts**: Monthly sales and profit trends
  * **Stacked Bars**: Country-wise net sales
  * **Matrix Table**: Buyer type vs. Sales, Profit, ROI
  * **Treemap/Bar Charts**: Discount bands and product performance
  * **Slicers**: Region, Buyer Type, Discount Band, Product

### 🔹 Step 3: Insight Derivation

* Generated in-depth business insights (see below).
* Created storytelling elements in the PDF for executive decision-making.

---

## 📌 Key Insights

### 💵 Profitability

* **Gross Sales**: 98.89M | **Net Sales**: 91.85M → Discounts \~7.18%
* **Net Profit**: 12.96M → Net Margin \~14.1%
* Action: **Review high-cost buyer segments and excessive discounts**.

### 📈 Monthly Sales Trends

* **Q4 Dominance**: Strongest months – October (12.4M), November (12.0M)
* **November Dip** (5.4M): Likely due to inventory, promotion, or market factors.
* Recommendation: **Launch recovery campaigns in Q2 and fix Q4 issues**.

### 🌍 Country-wise Sales

* Focus in **Southeast Asia**; **Africa and South America** are untapped.
* Suggests potential to **expand into emerging markets** with geo-targeted strategies.

### 👥 Buyer Segment Analysis

* **Corporations** are draining profit margins.
* **Resellers and Supermarkets** yield high ROI despite low volumes.

### 🎯 Discount Band Effect

* Clear inverse relation between discount and ROI.
* Recommend: **Value-based pricing, segment-based offers**.

### 📷 Product Performance

* **Camera 3**: Star performer → Top sales, highest profit, best weekday (Thursday).
* Other cameras are plateauing.
* Suggest: **Scale Camera 3**, offer bundles, and discount slow SKUs selectively.

---

## 🚀 Strategic Recommendations

| Focus Area           | Action Items                                                         |
| -------------------- | -------------------------------------------------------------------- |
| ❌ Low ROI Segments   | Audit/Exit corporation deals; reprice for MiniMarkets                |
| ✅ High ROI Buyers    | Upsell to Resellers & Supermarkets with incentive-based deals        |
| 💲 Discount Policy   | Reduce flat discounts; use behavioral/tiered pricing                 |
| 📦 Product Strategy  | Expand Camera 3 production; bundle accessories; drop underperformers |
| 🌐 Market Expansion  | Launch pilots in Africa and LatAm; use localized marketing           |
| 📅 Seasonal Planning | Campaigns in Q2 and Q3; fix bottlenecks in Q4 strategies             |

---

## 🖥️ How to Reproduce

1. Download this repository and open the `.pbix` file:

   ```bash
   git clone https://github.com/Harshita-bioinfo/Electronics-Sales-Dashboard.git
   cd Electronics-Sales-Dashboard
   ```
2. Open `Sales_Dashboard.pbix` using **Power BI Desktop**.
3. Use slicers to filter by Month, Buyer Type, Region, Product, and Discount Band.
4. Analyze visual insights or export PDF/PowerPoint from the dashboard.

---

## 🔁 Development Flow

```
Data Import → Cleaning & Enrichment → Power BI Visualization → Business Insights → Recommendations
```

---

