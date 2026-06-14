# 📊 HR Workforce Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Tool-Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![Type](https://img.shields.io/badge/Type-Learning_Project-blue?style=flat-square)

---

## 📌 Overview

This is a small practice project built to learn the basics of **Power BI report design** - layout, navigation, visuals, and conditional formatting.

The dataset is **mock HR data** (311 employees), covering department, position, salary, performance, satisfaction, and turnover information.

This was my **first Power BI project**, focused on getting comfortable with the tool rather than producing a deep analytical report.

---

## 📄 Pages

### 1. Executive Summary

A high-level overview of the workforce, with KPI cards and breakdown charts:

- **KPI cards**: Total Employees (311), Salary Expenses ($21.5M), Turnover Rate (33.44%), Average Tenure, Absence Rate, Average Satisfaction, Average Age
- **Age Distribution** and **Gender Distribution** charts
- **Departure Reason** breakdown (top reasons: another position, unhappy, more money)
- **Turnover Rate by Department** - Production has the highest turnover (~39.7%)
- **Top Recruitment Sources** - Indeed and LinkedIn bring in the most hires
- **Workforce Metrics Overview by Dimension** - a table that switches between Department, Position, Gender, Citizenship, Age, Marital Status, and Ethnicity using button-based navigation

### 2. Workforce Database

A detailed, filterable employee-level table showing salary, tenure, absence rate, satisfaction score, recruitment source, gender, marital status, performance, retention risk, and ethnicity - with conditional formatting (color scales and icons) to highlight outliers like high absence rate or high retention risk.

---

## 💡 Quick Observations

- Production has the highest turnover rate (~40%) compared to other departments.
- "Another position" and "unhappy" are the top two reasons employees leave.
- Indeed and LinkedIn are by far the strongest recruitment channels.
- Satisfaction scores are fairly consistent (~3.7-4.0) across ethnicity groups.

---

## 🎯 What I Practiced

- Building KPI cards and combining them into a summary page
- Using bar charts, donut charts, and funnel-style charts for different data shapes
- Adding a button-based dimension switcher (bookmarks / field parameters)
- Conditional formatting on tables (color scales, icons)
- Page navigation between Executive Summary and Workforce Database

---

## 🗂️ Files

| File | Description |
|---|---|
| `HR-WORKFORCE-DASHBOARD.pbix` | The Power BI report file (mock data, 2 pages) |
