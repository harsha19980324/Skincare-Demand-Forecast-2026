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
  <img src="https://github.com/user-attachments/assets/c19793a3-4c87-4975-81ca-973878251d23" alt="Forecast Dashboard" width="800" style="border:2px solid #0078D4; border-radius:8px; box-shadow:0 4px 8px rgba(0,0,0,0.1);"/>
  <br><em>Forecast Dashboard: Monthly forecasts, WMA growth, stockout % and safety stock</em>
</p>

---

### 🌊 Sheet 2 — Seasonality Heatmap

- Color-coded SI per SKU per month
- Dark teal = peak, red = trough
- Based on **demand quantity**, not sales, to avoid stockout bias

<p align="center">
  <img src="https://github.com/user-attachments/assets/4d9ebcc7-5c93-43ad-a2c7-01b2c356c8ae" alt="Seasonality Heatmap" width="800" style="border:2px solid #0078D4; border-radius:8px; box-shadow:0 4px 8px rgba(0,0,0,0.1);"/>
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

## 📄 Project Summary

<p align="center">
  <a href="https://github.com/user-attachments/files/26182633/project_summary.pdf" target="_blank">
    <img src="https://img.shields.io/badge/Download-PDF%20Summary-blue?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" />
  </a>
</p>

<div align="center" style="background: #f8f9fa; padding: 20px; border-radius: 12px; border: 2px solid #0078D4; box-shadow: 0 4px 12px rgba(0,0,0,0.1); max-width: 600px; margin: 30px auto;">
  <h3 style="color: #00BCF2; margin: 0 0 10px;">Get in Touch</h3>
  <p style="margin: 5px 0; color: #333;">
    <strong>Harsha Jayawardhana</strong>
  </p>
  <p style="margin: 10px 0;">
    <a href="harshakunkuma98@gmail.com" style="color: #D83B01; text-decoration: none;">harshakunkuma98@gmail.com</a> • 
    <a href="https://www.linkedin.com/in/harsha-jayawardhana-5bbb85216/" target="_blank">LinkedIn</a> • 
    <a href="https://github.com/harsha19980324" target="_blank">GitHub</a>
  </p>
  <p style="margin: 5px 0; font-size: 14px; color: #555;">
    <em>Love open-source? Let’s collaborate!</em>
  </p>
</div>
