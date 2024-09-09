# Vodafone-Challenge
Data Science , Analysis and Visualization  analyze resource allocation for Vodafone’s Project Management Office - Customer Demand and Capacity Planning Allocation Team. Includes data preprocessing, capacity planning, and visualization using Python, SSIS, and Tableau.

## Introduction
This project analyzes the resource allocation for Vodafone’s Project Management Office - Customer Demand and Capacity Planning Allocation Team. The goal is to provide a reporting solution to analyze resources per project and anticipated free capacity for each resource while running demand/supply gap analyses.

## Explaining Raw Data
The raw data includes employee codes, month data, and resource allocation details. Python was used to clean the data by extracting employee codes, handling null values, and applying table functions to calculate measures like total allocated hours, remaining capacity, and auto rates.

## Preprocessing (DWH)
Data was preprocessed using SSIS for integration and transformation. A Star Schema model was applied, and fact tables and dimension tables were created for employees, dates, and regions. SSAS cubes were used for multidimensional analysis.

## Data Visualization (Tableau & Power BI)
Tableau was utilized to visualize the results:
- **Utilization Rate by Region (Map View):** Heatmaps to display workload distribution.
- **Department Utilization Rates:** Insights into which departments are over or under-utilized.
- **Top 10 Employees' Utilization:** Highlights overburdened employees.
- **Allocated vs. Contracted Hours:** Displays fluctuations in workload distribution over the year.
