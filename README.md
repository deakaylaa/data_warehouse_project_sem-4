# Workforce Performance Management: Data Warehouse & BI Dashboard

This project is a collaboration between **Dea Kayla Putri Darusman** and **Dinda Ayu Permatasari**. We developed a complete Data Warehouse system and an interactive dashboard to monitor and predict employee performance.

---

## Project Overview
* **Tools**: Power BI, Pentaho (PDI), SQL, and Python.
* **Dataset**: Workforce Management Data.
* **Focus**: ETL Processes, Performance Clustering, and Salary Forecasting.

## Research Questions
1. How to design a Data Warehouse (Fact and Dimension tables) for workforce data?
2. What are the performance patterns of employees based on clustering?
3. How to predict future performance trends and salary increases?

## Repository Structure
* **ETL Files (`.ktr`)**: Pentaho transformations for Employee, Attendance, Task, and Promotion data.
* **Database (`.sql`)**: SQL script for Workforce Management schema.
* **Analysis (`.ipynb`)**: Jupyter Notebooks for clustering and forecasting analysis.
* **Dashboard (`.pbix`)**: Interactive Power BI dashboard file.

## Data Processing (ETL)
We used **Pentaho Data Integration** to transform raw data into a structured Data Warehouse:
* **Dimensions**: `dim_employee`, `dim_position`, `dim_grade`, `dim_attendance`, `dim_task`, and `dim_time`.
* **Facts**: `fact_attendance_evaluation`, `fact_promotion`, and `fact_task_performance`.

## Dashboard Key Insights
Our Power BI dashboard provides several key metrics:
* **KPI Overview**: Real-time tracking of Total Tasks, Working Hours, and Attendance.
* **Employee Clustering**: Segmenting employees into categories: *Sangat Baik, Baik, Cukup,* and *Tidak Aktif*.
* **Performance Trends**: Visualization comparing Actual vs. Predicted performance.
* **Salary Prediction**: Estimated next salary and promotion duration based on current performance.

## Tech Stack
* **Pentaho (PDI)**: For ETL (Extract, Transform, Load) processes.
* **SQL**: For data warehousing and schema management.
* **Python**: For data analysis, clustering, and forecasting.
* **Power BI**: For professional data visualization and dashboarding.
  
<img width="1264" height="727" alt="image" src="https://github.com/user-attachments/assets/a90fb9c1-c112-4a2a-b14c-ba945393a488" />
---
*Created as a Final Project for Data Warehouse Practice.*
