# 🍽️ Restaurant Data Analysis & KPI Dashboard

This project focuses on analyzing global restaurant data using **Excel** and **Power BI**. The goal is to build a robust **data model**, perform **KPI analysis**, and develop an **interactive dashboard** for deriving insights into restaurant openings, pricing, ratings, and service offerings.

---

## 📁 Project Overview

- **Domain:** Hospitality / F&B
- **Tools Used:** Microsoft Excel, Power BI
- **Dataset Format:** Excel Workbook
- **Data Sources:** Multiple sheets within a single Excel file

---

## 📊 Objectives

### 📦 1. Data Modeling
- Built a **data model** by linking relevant tables from Excel.
- Established proper relationships between dimension and fact tables.

### 📅 2. Calendar Table Creation
- Created a dynamic **calendar table** using `Datekey_Opening` (min to max date).
- Added time intelligence columns:
  - `Year`
  - `MonthNo`
  - `MonthFullName`
  - `Quarter` (Q1–Q4)
  - `YearMonth` (e.g., 2024-Jan)
  - `WeekdayNo`
  - `WeekdayName`
  - `FinancialMonth` (April = FM1, ..., March = FM12)
  - `FinancialQuarter` (e.g., FQ-1)

### 💵 3. Currency Conversion
- Converted **Average Cost for Two** from local currencies to **USD** using standard conversion logic.

---

## 📈 Key KPI Analysis

| Metric | Description |
|--------|-------------|
| 📍 **Restaurant Distribution** | Count of restaurants by **City** and **Country** |
| 🕓 **Opening Timeline** | Number of restaurants opened by **Year**, **Quarter**, and **Month** |
| ⭐ **Ratings Breakdown** | Count of restaurants by **Average Ratings** |
| 💰 **Price Buckets** | Grouped restaurants into custom buckets based on **Average Price** |
| 🍽️ **Dining Options** | Percentage distribution for: <br> - `Has_Table_booking` <br> - `Has_Online_delivery` |
| 🍜 **Cuisine Trends** | Visualized cuisine preferences by **city** and **ratings** |
| 🧠 **Custom KPIs** | Explored patterns in cuisines, service quality, and pricing for competitive insights |

---

## 📊 Dashboard Highlights

An **interactive Power BI dashboard** was created to visualize:
- Time-based openings
- Cuisine trends
- Ratings and service features
- Custom filter panels for city, price, and delivery


## 🛠️ Tools & Techniques

- Excel: Preprocessing, relationship mapping
- Power BI: DAX, data modeling, dynamic measures, visuals
- Time Intelligence: Custom calendar table with financial logic
- Visualizations: Bar, column, donut, slicers, KPI cards

---

## 🔍 Learning Outcomes

- Built a **calendar table** with fiscal calendar logic
- Performed **data modeling** and relationship mapping
- Created **measures and calculated columns** using DAX
- Developed clean, user-friendly **Power BI dashboards**
- Gained insights into **restaurant performance and services**

---

## 📌 Additional Notes

> ✅ KPIs were not limited to predefined metrics. Custom metrics were explored for deeper insight into restaurant services, ratings, and profitability.

---

## 📎 License

This project is for educational and demonstration purposes only.

