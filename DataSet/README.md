# 📂 Dataset – Connectivity Analysis Dashboard

![Dataset](https://img.shields.io/badge/Data-Dataset-blue)
![Format](https://img.shields.io/badge/File%20Type-CSV-green)
![Schema](https://img.shields.io/badge/Model-Star%20Schema-orange)

---

## 📖 Overview

This folder contains the **datasets used to build the Connectivity Analysis Power BI Dashboard**.

The data is organized using a **Star Schema**, which is a common data modeling technique in analytics and data warehousing.

The dataset includes **one fact table** and **multiple dimension tables** used to analyze telecom connectivity trends across regions and years.

---

## 📊 Dataset Structure

### 📌 Connectivity_Fact_Table.csv

**Type:** Fact Table

Contains the main connectivity metrics used in the dashboard.

Key fields include:

* Total Population
* Total Subscribers
* Mobile Subscribers
* Internet Subscribers
* Telephone Subscribers

This table stores the **core analytical data** used for visualizations.

---

### 📅 Date_Dimension.csv

**Type:** Dimension Table

Contains **time-related information** used to analyze trends over time.

Example fields:

* Year
* Date identifiers

This table helps perform **time-based analysis** in the dashboard.

---

### 🌍 Geography_Dimension.csv

**Type:** Dimension Table

Contains geographic information used for regional analysis.

Example fields:

* Region
* State

This table enables **region-wise comparison of connectivity metrics**.

---

### 📈 Metric_Dimension.csv

**Type:** Dimension Table

Defines the different connectivity metrics used in the analysis.

Example fields:

* Metric Name
* Metric Category

This table helps organize and categorize telecom indicators.

---

## 🧩 Data Model

The dataset follows a **Star Schema Model**:

Fact Table
➡ Connectivity_Fact_Table

Dimension Tables
➡ Date_Dimension
➡ Geography_Dimension
➡ Metric_Dimension

This structure improves **query performance and analytical efficiency in Power BI**.

---

## ⚙️ Usage

These datasets are imported into **Power BI Desktop** and used to:

* Build relationships between tables
* Create interactive dashboards
* Analyze telecom connectivity trends
* Compare regional subscriber growth

---

## 📌 Note

All datasets are provided in **CSV format** for easy import into analytics tools such as:

* Power BI
* Excel
* Python
* SQL databases

