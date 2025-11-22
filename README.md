# 📊 Power BI Job Market Analytics Dashboards

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black) ![Data Analytics](https://img.shields.io/badge/Data%20Analytics-blue?style=for-the-badge) ![ETL](https://img.shields.io/badge/ETL-Power%20Query-green?style=for-the-badge)

## 📖 Project Overview

This repository showcases two advanced **Power BI dashboards** developed to analyze the 2024 Data Science job market.

While the project structure was inspired by a real-world curriculum from Luke Barousse, **every stage of development—from raw data extraction to final UI design—was implemented independently.** My primary objective was to master the full lifecycle of a Business Intelligence project, simulating the day-to-day responsibilities of a Data Analyst.

### 🎯 Project Purpose
I built this project to demonstrate proficiency in:
* **End-to-End Development:** Handling the entire workflow without relying on pre-made templates.
* **Advanced Analytics:** Using DAX for complex calculations rather than just drag-and-drop visuals.
* **User-Centric Design:** Creating interactive, decision-support tools for recruiters and job seekers.

---

## 📁 Repository Structure

```text
/powerbi-job-market-dashboards
│
├── dashboard-1/
│   ├── Job_Market_V1.pbix       # The multi-page exploratory dashboard
│   ├── screenshots/
│   │   ├── page1_high_level.png
│   │   └── page2_drillthrough.png
│
├── dashboard-2/
│   ├── Job_Market_V2.pbix       # The single-page executive dashboard
│   ├── screenshots/
│   │   └── dashboard_single_page.png
│
└── README.md
⚠ Note: Raw data files are not included for confidentiality reasons. The .pbix files contain the imported data model and can be viewed directly in Power BI Desktop.📊 Dashboard 1 – Job Market Insights (Exploratory V1)Structure: 2 Pages (Overview + Drill-Through)This dashboard is designed for deep exploration, allowing users to move from a high-level summary to granular details using advanced navigation features.✔ High-Level KPIsMarket Overview: Instantly view Total Job Count, Median Annual Salary, and Top Job Titles.Trend Analysis: Visualizes the most in-demand roles in the current market.✔ Deep-Dive (Drill-Through Feature)Users can select a specific job title (e.g., "Data Analyst") to access a detailed report containing:Salary Distribution: Min, Max, and Median salary ranges.Remote Work Analysis: Breakdown of Work-from-home vs. On-site opportunities.Top Platforms: Identification of which websites host the most postings.Geospatial Insights: A global map showing hiring hotspots.✔ InteractivityNavigation: Custom buttons and bookmarks for seamless page switching.Slicers: Dynamic filtering by Job Title and Region.[Insert Screenshot of Page 1 Here]Overview Page: High-level market stats.[Insert Screenshot of Page 2 Here]Drill-Through Page: Detailed view for a specific job title.📈 Dashboard 2 – Focused Market Dashboard (Executive V2)Structure: Single-Page Optimized LayoutThis version applies "Executive Dashboard" design principles, prioritizing efficiency and immediate insight for fast decision-making.✔ Core Metrics (KPIs)A streamlined top-bar display featuring:Job Volume: Total Job Count.Complexity: Average Skills required per Job.Compensation: Median Yearly & Hourly Salary.✔ Comparative VisualsSalary by Job Title: Clear bar charts ranking roles by earning potential.Skill Popularity: Dual analysis of top skills by both raw count and percentage of job postings.✔ UI/UX DesignDark Mode: High-contrast professional aesthetic.Single-View Architecture: Removes the need for navigation, presenting all critical data points at a glance.[Insert Screenshot of Dashboard 2 Here]The refined, single-page executive view.🛠 Skills DemonstratedCategoryTechniques & Tools AppliedETL & Data PrepData cleaning, type conversion, and creating custom columns using Power Query (M).Data ModelingImplemented Star Schema principles, managed cardinality, and optimized table relationships.DAX & CalculationsCreated explicit measures for KPIs, median aggregations, and conditional logic (CALCULATE, DIVIDE, ALLSELECTED).VisualizationUtilized Column, Bar, Line, Map, and New Card visuals; applied custom formatting.InteractivityIntegrated Drill-through filters, Bookmarks, Page Navigation, and Slicers.Design & StorytellingVisual hierarchy planning, consistency in color themes, and usability optimization.
