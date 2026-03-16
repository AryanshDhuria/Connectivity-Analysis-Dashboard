# 📊 Connectivity Analysis Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?logo=powerbi\&logoColor=black)
![Domain](https://img.shields.io/badge/Domain-Telecom%20Analytics-blue)
![Dataset](https://img.shields.io/badge/Data-CSV-green)
![Visualization](https://img.shields.io/badge/Visualization-Dashboard-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

The **Connectivity Analysis Dashboard** is a Power BI project that analyzes telecommunication connectivity trends across regions and years.

The dashboard visualizes **population growth, telecom subscriber distribution, and connectivity penetration**, helping identify patterns in telecom adoption and regional connectivity differences.

---

## 🖼 Dashboard Preview

![Connectivity Dashboard](Report.png)

---

## 🎯 Project Objectives

* Analyze telecom connectivity trends over time
* Compare population vs subscriber growth
* Identify regions with high and low telecom penetration
* Create interactive visualizations for telecom data analysis

---

## 🛠 Tools & Technologies

* **Power BI** – Dashboard development
* **DAX** – Measures and calculations
* **CSV** – Dataset storage
* **Data Modeling** – Relationship creation

---

## 📂 Project Structure

```
Connectivity-Analysis-Dashboard
│
├── README.md
├── Report.png
│
└── dataset
    ├── Connectivity_Fact_Table.csv
    ├── Date_Dimension.csv
    ├── Geography_Dimension.csv
    ├── Metric_Dimension.csv
    └── README.md
```

---

## 📊 Key Dashboard Metrics

* Total Population: **58.17K**
* Total Subscribers: **30.13K**
* Connectivity Rate: **48.20%**
* Mobile Subscribers: **20.20K**
* Internet Subscribers: **9.55K**
* Telephone Subscribers: **387**

---

## 📈 Key Insights

* Telecom subscriber numbers increased steadily over time
* North region has the highest number of subscribers
* Northeast region has comparatively lower connectivity penetration
* Mobile connectivity dominates over traditional telephone connections
* Internet adoption is gradually increasing

---

## 📐 Example DAX Measure

```
Connectivity Rate =
DIVIDE([Total Subscriber], [Total Population]) * 100
```

---

## ⚙️ Dashboard Features

* KPI cards for key metrics
* Connectivity rate gauge visualization
* Trend analysis using line charts
* Regional comparison using bar charts
* Interactive filters for Region, State, and Year

---

## 👨‍💻 Author

**Aryansh Dhuria**


GitHub:
https://github.com/AryanshDhuria
