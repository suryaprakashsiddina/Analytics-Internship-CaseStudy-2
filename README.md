# Analytics-Internship-CaseStudy-2
Analytics Internship case study implementing a Sales, Inventory &amp; Operations Planning (SIOP) dashboard in Power BI. Features Power Query transformations, DAX calculations, data modeling, KPI tracking, and interactive executive reports.

# SIOP Reporting Dashboard – Power BI Case Study

## Overview

This repository contains my solution for the **Sales, Inventory & Operations Planning (SIOP) Reporting Case Study** completed as part of the Analytics Internship assessment.

The project demonstrates end-to-end Business Intelligence development using Microsoft Power BI, including data preparation, data modeling, DAX calculations, and dashboard design.

---

## Project Objectives

* Transform forecast snapshot data into a scalable reporting model.
* Compare forecast values across multiple planning snapshots.
* Integrate actual sales data with forecast data.
* Calculate Forecast Accuracy and Forecast Bias KPIs.
* Build an interactive executive dashboard.

---

## Technologies Used

* Microsoft Power BI Desktop
* Power Query
* DAX
* Excel

---

## Data Sources

* Forecast Data
* Actual Data
* Calendar Table
* Product Hierarchy
* Entity Mapping

---

## Dashboard Features

* Executive KPI Cards
* Revenue Analysis
* Non-Revenue Analysis
* CAPEX Analysis
* Forecast vs Actual Comparison
* Country-wise Performance
* Interactive Slicers
* Dynamic Lag Selection
* Forecast Trend Analysis

---

## Business KPIs

### Forecast Accuracy

Forecast Accuracy = 1 − ABS(Forecast − Actual) / Actual

### Forecast Bias

Forecast Bias = (Forecast − Actual) / Actual

---

## Data Model

A Star Schema model was implemented with:

* Forecast Fact Table
* Calendar Dimension
* Product Hierarchy Dimension
* Entity Mapping Dimension

This structure improves query performance and enables efficient filtering.

---

## Repository Structure

```
SIOP-Reporting-CaseStudy/

│── CaseStudy 2.pbix
│── Case Study Report.pdf
│── screenshots/
│     ├── Dashboard.png
│── README.md
```

---

## Skills Demonstrated

* Data Cleaning
* Power Query Transformations
* Data Modeling
* Star Schema Design
* DAX Measures
* Interactive Dashboard Design
* Business Intelligence Reporting

---

## Author

**Surya Prakash**

M.Tech – Artificial Intelligence & Data Science

Vellore Institute of Technology

