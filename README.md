# Bike Sales Analysis & Interactive Dashboard – Excel Beginner Project

This repository contains a beginner-level Excel project analysing bike sales data. The goal is to **clean, structure, and summarise sales data** and create an **interactive dashboard** to explore customer segments, regional trends, and product performance.

This project demonstrates fundamental data analysis skills in Excel and is the first of a planned series of three projects: Beginner, Intermediate, and Advanced.

---

## Project Overview

The workflow includes three main stages:

1. **Data Cleaning & Transformation**  
Standardised text and values using Excel shortcuts like Ctrl+F / Ctrl+H. Added a calculated column `Age Brackets` using a nested IF statement with three conditions to group customer ages for segmentation. Ensured consistency and correctness of categorical and numerical data to prepare it for analysis.


<img width="959" height="525" alt="image" src="https://github.com/user-attachments/assets/d593f4c4-fd26-4ab4-a426-b971f6503802" />


2. **Pivot Table Analysis**  
Pivot tables were created to explore different aspects of the dataset. The first summarises sales by product, gender, and average income, highlighting purchasing patterns across demographic groups. The second analyses commute distance against purchase decisions to understand how travel affects buying behaviour. The third examines customer segmentation by gender, age brackets, and purchase, revealing trends in purchasing across different age and gender groups. Each pivot aggregates metrics such as total purchases, average income, and buyer distribution, providing quick and actionable insights into top-performing segments and demographic trends.


<img width="956" height="524" alt="image" src="https://github.com/user-attachments/assets/d2636098-d1d3-4000-b703-744da608ef38" />


3. **Interactive Dashboard**  
An interactive dashboard was developed using the pivot tables and charts from the cleaned dataset. Slicers were incorporated for Marital Status, Cars (Yes/No), Occupation, Education, and Region, enabling dynamic filtering across multiple dimensions. The dashboard provides a clear, real-time view of key metrics and trends, allowing quick exploration of customer behaviour and sales performance across segments.


<img width="697" height="365" alt="image" src="https://github.com/user-attachments/assets/80c3587c-49a1-4110-8c29-8260b352eeab" />


---

## Repository Files

| File | Description |
|------|-------------|
| `Raw_Bike_Sales_Dataset.xlsx` | Original dataset with no transformations. |
| `Bike_Sales_Workbook.xlsx` | Cleaned dataset with calculated `Age Brackets` column and pivot tables. |
| `Dashboard.xlsx` | Interactive dashboard built from pivot tables with slicers for dynamic filtering. |

---

## How to Use

1. Open **`Bike_Sales_Workbook.xlsx`** to explore the cleaned data and review the `Age Brackets` calculation.  
2. Examine the **Pivot Tables** to understand sales and customer segment summaries.  
3. Open **`Dashboard.xlsx`** to interact with the dashboard and explore trends using slicers.  

---

## Technical Details

- **Excel Skills Demonstrated:**  
  - Data cleaning and standardiSation  
  - Nested `IF` formulas for calculated columns  
  - Pivot tables for aggregation and analysis  
  - Interactive dashboard creation with slicers and charts  

- **Analytical Skills Demonstrated:**  
  - Segmenting customers and products for insight  
  - Aggregating metrics for reporting  
  - Building visual tools for data-driven decision-making  

---

This project demonstrates a full cycle of data analysis in Excel, from cleaning and structuring raw data to summarizing key metrics with pivot tables and visualizing insights in an interactive dashboard. It showcases the ability to segment customers, identify trends, and present actionable insights in a clear and accessible way. The repository provides both the cleaned dataset and supporting pivot tables, allowing others to explore the workflow and replicate the analysis.
