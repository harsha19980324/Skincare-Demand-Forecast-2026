# 📊 Skincare Demand Forecast 2026

## 🚀 Overview

This project presents a **comprehensive Excel-based demand forecasting solution** for 20 skincare SKUs across 8 product categories.  

The model uses **historical demand data** (2023–2025) to generate **monthly forecasts for 2026**, incorporating:

- Weighted Moving Average (WMA) growth
- Holt's smoothing for trend adjustment
- Blended Forecast
- Seasonality Index (SI)
- Stockout intelligence and safety stock calculations

---

## 📂 Project Structure

### 📊 Sheet 1 — Forecast Dashboard

- All 20 SKUs with:
  - WMA growth
  - Holt's smoothing
  - Blended forecast
  - Revenue estimates
  - Stockout % and safety stock
  - Reorder point (ROP)
- Monthly breakdown (Jan–Dec 2026)

<p align="center">
  <img src="images/forecast_dashboard.png" alt="Forecast Dashboard" width="800" style="border:2px solid #0078D4; border-radius:8px; box-shadow:0 4px 8px rgba(0,0,0,0.1);"/>
  <br><em>Forecast Dashboard: Monthly forecasts, WMA growth, stockout % and safety stock</em>
</p>

---

### 🌊 Sheet 2 — Seasonality Heatmap

- Color-coded SI per SKU per month
- Dark teal = peak, red = trough
- Based on **demand quantity**, not sales, to avoid stockout bias

<p align="center">
  <img src="images/seasonality_heatmap.png" alt="Seasonality Heatmap" width="800" style="border:2px solid #0078D4; border-radius:8px; box-shadow:0 4px 8px rgba(0,0,0,0.1);"/>
  <br><em>Seasonality Heatmap — highlights peak and low-demand months per SKU</em>
</p>

---

### ⚠️ Sheet 3 — Stockout Intelligence

- 3-year stockout rate, fill rate, lost units, lost revenue
- Safety stock and reorder point
- Sorted by severity to prioritize inventory management

---

### 📦 Sheet 4 — Category Summary

- Aggregated metrics for 8 product categories
- Growth rates, service levels, and stockout risk

---

### 📈 Sheet 5 — Charts

- 4 embedded charts:
  - Demand history vs forecast
  - Stockout vs fill rate
  - Average seasonality curve
  - Lost revenue by SKU

---

### 📋 Sheet 6 — Methodology

- Full explanation of:
  - Formulas used
  - Assumptions made
  - Parameter choices
  - Limitations

---

## 🔑 Key Findings

- **Total 2026 Forecast:** 38,399 units
- **Revenue Forecast:** ~$1.13M
- **3-Year Estimated Lost Revenue from Stockouts:** ~$344K
- **Highest Stockout Risk SKUs:**
  - Body Lotion (81%)
  - Moisturizer, Eye Cream, CC Cream, Face Scrub (78%)
- **Strongest Growth SKUs:**
  - BB Cream (+12.5%)
  - Face Scrub (+10.6%)
  - Night Cream (+10.7%)
  - CC Cream (+9.9%)
- **Critical Insight:** Forecast was run on **demand quantity**, not sales, to capture SKUs with stockout issues.

---

## 🎯 Business Value

This model helps businesses:

- Reduce stockouts
- Optimize inventory and safety stock
- Improve forecasting accuracy
- Make data-driven purchasing decisions
- Align inventory with seasonal demand

---

## 🛠️ Tools Used

- Microsoft Excel
- Pivot Tables
- Data Visualization (heatmaps, charts)
- Forecasting methods: WMA, Holt's smoothing

---

## 📌 How to Use

1. Download the Excel workbook
2. Review historical demand data (2023–2025)
3. Analyze seasonality patterns and stockout risks
4. Use the 2026 forecast to optimize inventory and plan purchases

---

## 📥 Files

- `forecast_dashboard.png` — Main dashboard screenshot  
- `seasonality_heatmap.png` — Seasonality visualization  
- `skincare_forecast_2026.xlsx` — Full workbook  
- `project_summary.pdf` (optional) — Overview document

---

## 👨‍💻 Author

Harsha K.  

💼 Open for freelance work in:

- Demand Forecasting
- Inventory Management
- Excel Dashboard Development

---

## ⭐ If you found this useful

Please consider giving this repository a star!
