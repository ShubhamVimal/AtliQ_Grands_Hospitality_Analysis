# 🏨 AtliQ Grands Hospitality Dashboard

A modern Power BI solution that turns raw hotel data into clear, actionable insights for **AtliQ Grands**, a five‑star hotel chain operating across India.

---

## 🌐 Live Dashboard (Interactive)

You can explore the live, interactive version of this Power BI dashboard hosted on the Power BI Service:

🔗 [Open Live Report](https://app.powerbi.com/view?r=eyJrIjoiZjNhNzMyNzUtNzA2OS00YzVlLWE4ZmEtMmJjOTNlYmY2YjkzIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
*(Best viewed on desktop in full-screen mode)*

---

## 📝 Overview
AtliQ Grands has served the luxury segment for 20+ years, but recent competition and poor decision-making have impacted their market position. To solve this, they adopted **Business & Data Intelligence** and partnered with a third-party analytics provider to turn historical data into actionable insights.

---

## 🎯 Project Goal
Build a Power BI dashboard that enables AtliQ Grands to:

- Track key metrics like revenue, occupancy, and booking trends  
- Analyze performance at platform and property levels  
- Monitor monthly and weekly changes  
- Support smarter, data-driven decisions to regain market share  

---

## 🗂 Data Sources

All data used in this project was provided as flat `.csv` files, including:

- `fact_bookings.csv` – Main transactional data (bookings, dates, platforms, status)  
- `fact_aggregated_bookings.csv` – Pre-summarized booking metrics  
- `dim_date.csv` – Calendar table for time-based analysis  
- `dim_hotels.csv` – Hotel/property metadata  
- `dim_rooms.csv` – Room classifications  
- `meta_data_hospitality.txt` – Column definitions and metadata  

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Data modeling & dashboard design  
- **DAX** – Custom KPIs & calculations  
- **Power Query** – Data transformation & cleaning  
- **Power BI Service** – Report publishing & sharing  
- **GitHub** – Project versioning & documentation  

---

## ✨ Features & Techniques

- Custom KPIs: Revenue, Occupancy %, Avg Rating, RevPAR, Booking Success %, Realisation %, Cancel Rate %  
- Time intelligence: MoM & WoW % changes with icons and conditional formatting  
- Advanced tooltips: Platform- and property-level trend comparisons using line charts  
- Interactive filters: Slicers by City, Property, Month, Week, Platform, and Status  
- Modern visuals: Card (new), matrix, line, stacked bar, donut, clustered column  
- Clean theming: Hospitality-focused color palette, typography, layout, and spacing  
- DAX-driven insights: 30+ optimized measures for performance and trend analysis  
- Tooltip-based deep dives without adding visual clutter or extra pages  

---

## 📸 Dashboard Views

### 🧩 Mock‑up Design  
![Mock‑up](https://github.com/ShubhamVimal/AtliQ_Grands_Hospitality_Analysis/blob/main/mock_up_dashboard.png)

---

### ✅ Final Dashboard

#### 🏠 Home Page  
![Home](https://github.com/ShubhamVimal/AtliQ_Grands_Hospitality_Analysis/blob/main/Home.PNG)

#### 📊 Overall Insights  
![Overall](https://github.com/ShubhamVimal/AtliQ_Grands_Hospitality_Analysis/blob/main/Overall_Insights.PNG)

#### 📅 Monthly Insights  
![Monthly](https://github.com/ShubhamVimal/AtliQ_Grands_Hospitality_Analysis/blob/main/Monthly_Insights.JPG)

---

## ✅ How to Use

1. Download the `.pbix` file from this repo  
2. Open it using **Power BI Desktop**  
3. Navigate through each page using buttons and slicers  
4. Apply filters to explore specific metrics or segments  

---

## ⭐ If You Found This Useful

Give this repo a ⭐ on GitHub if you found it helpful — your support is appreciated!
