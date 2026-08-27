# Data Jobs Dashboard with Power BI
![Dashboard Screenshot](Images/dashboard.png)

## Introduction

This dashboard was created to provide a clear and interactive view of the data job market, helping Job Seekers, Career Transitioners, and Professionals understand which skills are in demand and how different data-related roles compare in terms of salary.

Using a dataset of data job postings, this project transforms raw job-market data into meaningful insights such as job demand, top skills, number of skills required per job, and median compensation. The dashboard is designed to make it easier to explore the relationship between **job roles, required skills, and salaries** through interactive filtering and parameter-driven analysis.

## Skills Showcased

This project demonstrates several important Power BI concepts, including:

* ⚙️ **Data Transformation with Power Query:** Cleaned and prepared the raw job-posting data by handling data types, blanks, and transforming columns for analysis.

* 🧮 **DAX Measures:** Created measures to calculate important KPIs such as **Job Count, Skills Per Job, Median Yearly Salary, and Median Hourly Salary**.

* 📊 **Calculated Columns:** Created calculated columns to derive additional information from the existing dataset and support deeper analysis and visualizations.

* 🎛️ **Field/What-If Parameters:** Implemented parameters to dynamically switch between different metrics, allowing users to analyze **Job Count vs. Job Percent** and **Median Yearly Salary vs. Median Hourly Salary** without creating separate visualizations.

* 📈 **Interactive Visualizations:** Used bar charts and KPI cards to highlight the most in-demand skills and compare compensation across different job titles.

* 🖱️ **Interactive Slicers:** Added slicers for **Job Title** and **Country**, allowing users to dynamically filter the entire dashboard.

* 🎨 **Dashboard Design:** Designed a clean, dark-themed dashboard with clearly separated KPI and analytical sections to make important insights easy to understand.

## Dashboard Overview

### Page 1: Data Job Market Overview

This page provides a high-level overview of the data job market.

The KPI section highlights:

* **Total Job Count**
* **Average Skills Required Per Job**
* **Median Yearly Salary**
* **Median Hourly Salary**

The **Top Skills** visualization identifies the most frequently requested skills across job postings, helping users understand which technical skills are currently in demand.

The **High Paying Jobs** visualization compares different job titles based on their median compensation, making it easier to identify roles with stronger earning potential.

### Interactive Analysis

The dashboard also includes interactive controls that allow users to change the way information is presented.

The **Job Count / Job Percent parameter** allows users to switch between the absolute number of job postings and their percentage contribution.

Similarly, the **Median Yearly Salary / Median Hourly Salary parameter** allows users to switch between yearly and hourly compensation.

The **Job Title** and **Country** slicers further allow users to narrow the analysis and explore specific roles or geographic markets.

## Key Insights

This dashboard makes it possible to quickly answer questions such as:

* Which skills are most frequently requested in data-related jobs?
* How many jobs are available across different roles?
* Which data job titles have the highest median salaries?
* How many skills are typically required for a data job?
* How does compensation change when viewed as yearly versus hourly salary?
* What happens to the job market metrics when filtering by a specific job title or country?

## Conclusion

This project demonstrates how **Power BI, DAX Measures, Calculated Columns, Parameters, and Interactive Slicers** can be combined to transform raw job-posting data into an interactive career analytics dashboard.

Rather than simply displaying static numbers, the dashboard allows users to dynamically explore the data and compare **job demand, required skills, and salary levels** based on their specific interests. It showcases my ability to perform data transformation, build analytical calculations, create interactive visualizations, and design a Power BI dashboard focused on real-world decision making.
