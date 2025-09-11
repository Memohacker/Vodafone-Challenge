# 📊 Vodafone-Challenge

**Data Science | Analysis | Visualization**
Analyze **resource allocation** for Vodafone’s **Project Management Office – Customer Demand & Capacity Planning Allocation Team** using **Python, SSIS, and Tableau**.

---

## 🚀 **Introduction**

This project focuses on analyzing **resource allocation** within Vodafone’s PMO to:
✅ Measure resource utilization per project
✅ Identify free capacity for each resource
✅ Perform **demand vs. supply gap analysis**
✅ Provide actionable insights through **interactive dashboards**

---

## 🗂 **Raw Data Overview**

The dataset contains:

* 👤 **Employee Codes** – Unique identifiers for resources
* 📅 **Month-wise Data** – Time-series data for allocation trends
* ⏳ **Resource Allocation Details** – Total hours, contracted hours, and remaining capacity

**Preprocessing (Python):**

* 🧹 Data cleaning (null handling, formatting, code extraction)
* 📊 Aggregating measures:

  * **Total Allocated Hours**
  * **Remaining Capacity**
  * **Auto-Calculated Utilization Rates**

---

## 🛠 **ETL & Data Warehouse (DWH)**

Data was processed using **SSIS** to create a **Star Schema** for easy analysis.

📐 **Star Schema Includes:**

* **Fact Table:** Resource Allocation
* **Dimension Tables:**

  * Employee
  * Date
  * Region / Department

📦 **SSAS Cubes:** Used for **multidimensional analysis** (OLAP) enabling fast slicing, dicing, and drill-downs.

---

## 📊 **Data Visualization (Tableau & Power BI)**

Built **interactive dashboards** for decision-makers:

🔹 **Utilization Rate by Region (Map View)**

> Heatmaps showing which regions are overloaded or under-utilized.

🔹 **Department Utilization Rates**

> Helps managers quickly identify departments with spare capacity or excessive workload.

🔹 **Top 10 Employees by Utilization**

> Pinpoints the most overburdened employees for workload balancing.

🔹 **Allocated vs. Contracted Hours Trend**

> Monthly trend chart to monitor **demand fluctuations** throughout the year.

---

## 🖼 **Sample Dashboard (Tableau)**

[Tableau work.pdf](https://github.com/user-attachments/files/22269088/Tableau.work.pdf)

---

## 🛠 **Tech Stack**

| Tool                       | Purpose                                  |
| -------------------------- | ---------------------------------------- |
| **Python (Pandas, Numpy)** | Data cleaning & preprocessing            |
| **SSIS**                   | ETL & Data Integration                   |
| **SSAS**                   | OLAP Cubes for multidimensional analysis |
| **Tableau / Power BI**     | Data Visualization & Dashboarding        |

---

## 📈 **Key Outcomes**

✅ Improved visibility into **resource utilization**
✅ Early detection of **demand-supply gaps**
✅ Optimized **capacity planning** for Vodafone PMO
✅ Faster decision-making with **self-service BI dashboards**

---

## 📌 **Next Steps**

* 🔄 Automate data refresh for real-time dashboards
* 🤖 Add ML-based **workload prediction**
* 📲 Deploy interactive dashboards for wider access
