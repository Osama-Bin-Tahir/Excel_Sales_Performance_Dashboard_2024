# 📊 Sales Performance Intelligence Dashboard  
### An Interactive Executive Dashboard in Microsoft Excel 2024 (.xlsm)

🚀 A fully interactive, end-to-end Excel dashboard designed to track **sales performance vs. targets**, identify top and low performers, and deliver decision-ready insights through clean executive visuals.

---

## 📌 Project Overview

This project represents my first complete end-to-end business dashboard build using **Microsoft Excel 2024**.  

The objective was to transform a flat sales dataset into a dynamic, interactive performance monitoring system that answers key business questions instantly:

- Who are the top-performing sales executives?
- Who is underperforming?
- How close are we to achieving sales targets?
- How does performance vary across regions?

The final output is a **macro-enabled (.xlsm) Excel dashboard** powered by PivotTables, PivotCharts, Slicers, and VBA navigation features.

---

## 🎯 Background & Motivation

While learning Excel analytics, I noticed a critical gap between:

- Knowing Excel features (PivotTables, charts, slicers)  
- Building a structured, decision-focused business dashboard  

This project was built to practice the *complete analytics workflow*:

1. Structuring raw data properly  
2. Creating calculated performance metrics  
3. Designing analytical PivotTables  
4. Connecting slicers across multiple views  
5. Building a clean executive layout  
6. Adding VBA macros to simulate app-like navigation  

The focus was not just analysis — but **clarity, usability, and decision impact**.

---

## ❓ Business Questions Answered

This dashboard provides instant insights into:

- 🏆 **Top Performers:** Highest-selling sales executives  
- 📉 **Low Performers:** Bottom-performing executives  
- 🎯 **Target Achievement:** Highest Target Hit %  
- 📊 **Performance Gap:** Away From Target %  
- 🌍 **Regional Performance:** Dynamic filtering by region/city  
- ⚖️ **Quick Comparisons:** Performance spread at a glance  

---

## 🛠 Tools & Technologies

- **Microsoft Excel 2024**
- PivotTables (Top/Bottom N analysis)
- PivotCharts (Bar & Line visualizations)
- Slicers (Dynamic filtering)
- VBA Macros (.xlsm) for dashboard navigation
- GitHub (Version control & portfolio presentation)

---

## 📂 Dataset Structure

The dataset includes:

- `Emp Code`
- `Sales Executive`
- `Region`
- `Day1` – `Day5` (Daily sales)
- `Total Sales` (Calculated)
- `Target`
- `Target Hit %` (Calculated)
- `Away From Target %` (Calculated)

---

## 🧮 Key Calculations

- **Total Sales** = Sum of Day1–Day5  
- **Target Hit %** = Total Sales / Target  
- **Away From Target %** = 100% − Target Hit %  

These calculations form the core KPIs used throughout the dashboard.

---

## 📊 Dashboard Components

The dashboard contains 4 primary analytical views:

- 🥇 **Top 5 Executives by Total Sales**
- 📉 **Bottom 5 Executives by Total Sales**
- 🎯 **Top Performers by Target Hit %**
- 📊 **Highest Gap (Away From Target %)**

All visuals are connected via slicers, allowing real-time filtering by region/city.

---

## 📈 Key Insights (Sample View)

- Clear separation between top and low sellers
- Target achievement varies significantly (mid-40% to mid-70% in sample)
- Away From Target % quickly highlights actionable underperformance
- Regional filtering changes performance rankings instantly

---

## 🧠 What I Learned

This project strengthened my understanding of:

- Designing Top/Bottom N PivotTable reports
- Connecting slicers across multiple PivotTables
- Structuring raw datasets for scalable dashboards
- Creating clean, executive-friendly layouts
- Basic VBA integration for improved dashboard interactivity
- Visual storytelling using Excel

---

## 🔄 Future Improvements

Planned enhancements:

- KPI summary cards (Total Sales, Avg Target Hit %, Best/Worst Executive)
- Daily sales trend visualization (Day1–Day5)
- Auto-refresh + last updated timestamp
- Enhanced VBA documentation
- Improved UI buttons for smoother navigation

---

## ▶️ How to Use

1. Download the `.xlsm` file from this repository.
2. Open in **Microsoft Excel (Desktop version)**.
3. Click **Enable Editing** and **Enable Content** (macros).
4. Use slicers and navigation buttons to filter and explore.
5. Refresh PivotTables after updating `Raw_Data`.

> ⚠️ Note: This is a portfolio/learning dataset built for analytical demonstration purposes.

---

## 🖼 Dashboard Preview

![Dashboard Preview](/Dashboard_Preview.PNG)

---

## 💡 Final Note

This project reflects my transition from learning Excel features to building structured, decision-ready business intelligence tools.

It demonstrates not just technical skill — but analytical thinking, data structuring, and dashboard design discipline.

---
