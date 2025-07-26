# 🚖 Uber Fare Data Analysis (Power BI Project)

**Course**: Introduction to Big Data Analytics (INSY 8413)
**Instructor**: Eric Maniraguha
**Student**: Honore Munyemana (**ID: 25594**)
**Submission Date**: July 25, 2025

---

## 📌 Objective

Analyze Uber ride data to uncover fare patterns, peak hours, weekday trends, and geo distributions using **Python (Pandas)** and **Power BI**.

---

## 🧪 Methodology

### 🔹 1. Data Preparation (Python)

* Loaded raw dataset with Pandas
* Assessed structure, data types, and missing values
* Cleaned nulls and filtered invalid entries (e.g., zero coordinates)
* Performed exploratory statistics: mean, median, mode, std, quartiles, and outliers
* Engineered new features:

  * `hour`, `day`, `month` from `pickup_datetime`
  * `weekday` classification
  * `peak_indicator` based on commute hours
* Exported cleaned and enhanced dataset to `uber_enhanced.csv` for Power BI

### 🔹 2. Data Analysis & Visualization (Power BI)

* Imported `uber_enhanced.csv`
* Built key visuals:

  * **Fare Distribution** – Histogram
  * **Box Plot** – Done using **Python** due to sign-in limitation in Power BI visual marketplace
  * **Hourly Ride Volume** – Bar chart
  * **Monthly Trends** – Column chart
  * **Weekday Patterns** – Bar chart
  * **Geo Map** – Bubble map using latitude & longitude
* Added slicers for month, weekday, and peak indicators
* Used consistent titles, labels, and design for clarity

---

## 📈 Key Insights

* Most rides cost between **\$5–\$15** — showing dominance of short-distance trips
* Clear **morning (7–9 AM)** and **evening (5–7 PM)** ride peaks
* **Friday** shows highest ride frequency — possible weekend travel boost
* Pickup locations are **densely clustered in central NYC**, especially Manhattan
* Python boxplot reveals a few **extreme fare outliers** likely due to long rides or anomalies

---

## 📂 Files Included

* `uber_analysis.ipynb` – Python data prep and EDA
* `uber_enhanced.csv` – Final dataset used in Power BI
* `uber_fare_dashboard.pbix` – Interactive dashboard
* `screenshots/` – Evidence of each step and final visuals
* `README.md` – Project overview and report (this file)

---

## ✅ Conclusion

This end-to-end pipeline demonstrates how to clean, explore, and visualize transportation data effectively. Despite visual marketplace limitations, Python filled the gap for statistical visuals (boxplot). The Power BI dashboard is informative, well-organized, and ready for stakeholder decision-making.

---

## 🌐 GitHub Repository

[https://github.com/honore-munyemana/uber-fare-analysis](https://github.com/honore-munyemana/uber-fare-analysis)
