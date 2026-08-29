# 🏥 Hospital Resource Intelligence Dashboard

<p align="center">
  <img src="C:\Users\kambl\OneDrive\Documents\Projects\Hospital Resource Intelligence Dashboard\images\dashboard_preview.png" alt="Hospital Resource Intelligence Dashboard" width="1000">
</p>

<p align="center">
  An interactive Power BI dashboard for analyzing hospital patient, operational, and financial performance.
</p>

---

## 📌 Project Overview

The **Hospital Resource Intelligence Dashboard** is an interactive Business Intelligence project developed using **Microsoft Power BI**.

It provides an executive-level overview of hospital performance by combining patient, operational, and financial metrics into a single interactive dashboard.

The dashboard helps users monitor hospital performance, analyze patient admissions, compare departments, evaluate patient satisfaction, and identify high-performing departments based on patient volume and revenue.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Monitor overall hospital performance using key KPIs.
- Analyze patient admission trends over time.
- Identify departments with the highest patient volume.
- Identify the top revenue-generating departments.
- Monitor patient satisfaction across departments.
- Track operational metrics such as waiting time and average length of stay.
- Analyze hospital performance using interactive filters.

---

## 📊 Dashboard Features

### Key Performance Indicators

The Executive Overview includes:

| KPI | Description |
|---|---|
| 👥 Total Patients | Total number of patients admitted |
| 💰 Total Revenue | Total hospital revenue |
| ⏱ Avg Waiting Time | Average patient waiting time |
| 🛏 Avg Stay | Average length of patient stay |
| ⭐ Avg Satisfaction | Average patient satisfaction score |
| 🔄 Readmission Rate | Percentage of patients readmitted |

---

## 📈 Visualizations

The dashboard contains the following visualizations:

### 📉 Patient Admissions Trend

Tracks patient admissions over time and helps identify changes and trends in hospital patient volume.

### ⭐ Patient Satisfaction by Department

Compares average patient satisfaction scores across hospital departments.

### 🏥 Top 3 Departments by Patient Volume

Identifies the three departments with the highest number of patient admissions.

### 💰 Top 3 Departments by Revenue

Identifies the three departments generating the highest revenue.

---

## 🎛 Interactive Filters

Users can interact with the dashboard using:

- 📅 Admission Date
- 🏥 Department
- 📍 City

These filters dynamically update the KPIs and visualizations.

---

## 🛠 Tools & Technologies

- **Microsoft Power BI** – Dashboard development and visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – KPI calculations and measures
- **PostgreSQL** – Data storage and management
- **Git & GitHub** – Version control and project hosting

---

## 🏗 Data Model

The Power BI data model includes:

### Fact_PatientAdmissions

Contains patient admission and hospital-related records used for analysis.

### Dim_Date

A date dimension used for time-based analysis and admission trend reporting.

### Measures

A dedicated table containing DAX measures used throughout the dashboard.

---

## 🧮 Key Metrics

The dashboard includes measures for:

- Total Patients
- Total Revenue
- Average Waiting Time
- Average Length of Stay
- Average Satisfaction
- Readmission Rate
- Revenue Per Patient
- Previous Month Revenue
- Revenue Growth Percentage

---

## 📂 Project Structure

```text
Hospital-Resource-Intelligence-Dashboard/
│
├── dataset/
│   └── hospital_data.csv
│
├── images/
│   └── dashboard_preview.png
│
├── Hospital Resource Intelligence Dashboard.pbix
│
└── README.md