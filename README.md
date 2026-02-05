# 🏨 GLOBAL HOSPITALITY PERFORMANCE & TREND ANALYSIS (2020–2025)
---

## 📌 Project Overview
This project provides a comprehensive analysis of the global hospitality industry, examining **50,000 total reviews** across **25 hotels**, **25 cities**, and **25 countries**. Using a combination of **SQL** for data engineering and **Power BI** for visualization, I identified a significant **44% decline in user engagement** for 2025 and traced it back to specific service quality failures in previous years.

## 🛠️ Technical Workflow

### 1. Data Engineering (SQL)
* **Data Cleaning:** Converted raw text date fields into standardized `DATE` formats using `str_to_date` for time-series analysis.
* **Database Schema:** Defined primary/foreign key relationships between `hotels`, `users`, and `reviews` to ensure data integrity.
* **Advanced Analytics:** Developed CTEs and Window Functions (like `LAG`) to calculate **Year-over-Year (YoY) Growth** and rank hotel performance.

### 2. Business Intelligence (Power BI)
* Developed interactive dashboards to track KPIs including average ratings, review volumes, and traveller demographics.
* Visualized seasonality trends and geographic performance across 25 global cities.

---

## 📈 Executive Insights

### **Critical Performance Trends**
* **The 2025 Slump:** After peak activity in 2023 and 2024, the platform experienced a **44% sharp decline** in active users.
* **Recovery Benchmark:** 2021 saw a **153% surge in users**, marking a strong post-pandemic recovery phase.
* **Seasonality:** Peak engagement consistently occurs during **June and July**, with secondary spikes in **November and December**.

### **Service Quality & Risk Factors**
* **Rating Drivers:** High performance is strongly driven by **Cleanliness, Comfort, Location, and Staff Quality**.
* **Major Risks:** The industry faces a systemic struggle with **Value for Money**; notably, **no hotel** achieved a rating of 9.0 or higher in this category.
* **The Root Cause:** The 2025 decline was fueled by dropping scores in **Comfort, Facilities, and Staff** during the 2023–2024 period.

### **Geographic & Segment Winners**
* **Top Cities:** **Dubai** and **Amsterdam** lead with the highest average rating of **9.05**.
* **Top Hotels:** **The Golden Oasis** and **Canal House Grand** are among the highest-rated properties.
* **Segment Needs:** **Couple travellers** (the largest group at 694 users) express the highest dissatisfaction with hotel **Facilities**.

---

## 📂 Repository Content
* **`/Data`**: Raw datasets (`hotels.csv`, `users.csv`, `reviews.csv`).
* **`/SQL`**: Scripts for ETL, data cleaning, and advanced business queries.
* **`/PowerBI`**: Interactive dashboard file (`hospitality.pbix`).
* **`/Reports`**: Final business insights and performance summary.

---

## 🚀 Conclusion & Recommendations
To reverse the 2025 decline, stakeholders should prioritize upgrading **Facilities** and improving **Staff training**, particularly in low-performing cities like **Cairo and Lagos**. Addressing the "Value for Money" gap is essential for long-term user retention.
