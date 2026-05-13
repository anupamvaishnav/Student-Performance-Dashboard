# Student-Performance-Dashboard

# 📊 Power BI Student Analytics Dashboard

A complete **Power BI Dashboard Project** built using **Power Query, Data Modeling, DAX Measures, Time Intelligence, Interactive Visuals, and Dashboard Design**.

This project analyzes:

- 📈 Student Scores
- 🧑‍🎓 Student Performance
- 📅 Attendance Trends
- ⚠️ Behavior Records
- 🏫 Class & Section Analysis

---

# 🚀 Project Features

## ✅ Data Cleaning (Power Query)

- Removed blank rows
- Changed data types
- Renamed columns & tables
- Cleaned and structured datasets

---

# 🗂 Dataset Tables

| Table Name | Description |
|---|---|
| Students_Dim | Student information |
| Scores_Fact | Student scores |
| Attendance_Fact | Attendance records |
| Behavior_Fact | Behavior/performance records |

---

# ⭐ Data Modeling

Implemented a proper **Star Schema** model using:

- Primary Keys
- Foreign Keys
- Relationships

---

# 📐 DAX Measures Used

## Basic Measures

```DAX
Total Score = SUM(Scores_Fact[Score])
```

```DAX
Average Attendance = AVERAGE(Attendance_Fact[AttendancePercentage])
```

```DAX
Total Students = DISTINCTCOUNT(Students_Dim[StudentID])
```

---

# 🧠 Advanced DAX Functions

Used:

- CALCULATE()
- FILTER()
- ALL()
- SUMX()
- COUNTX()
- AVERAGEX()
- SWITCH()
- RELATED()
- IF()
- DISTINCTCOUNT()

---

# 📅 Time Intelligence

Implemented:

- Year-over-Year Analysis
- Month-over-Month Trends
- Running Totals
- Forecasting
- Trend Analysis

Functions used:

```DAX
TOTALYTD()
```

```DAX
SAMEPERIODLASTYEAR()
```

```DAX
DATESINPERIOD()
```

---

# 📊 Dashboard Visuals

Used the following visuals:

- KPI Cards
- Line Charts
- Clustered Bar Charts
- Donut Charts
- Matrix Tables
- Slicers

---

# 🎯 Dashboard Capabilities

## ✔ Interactive Filtering

Added slicers for:

- Class
- Gender
- Section
- Date

---

## ✔ Drillthrough & Drilldown

Implemented:

- Drill Up/Down
- Drillthrough pages

---

## ✔ Conditional Formatting

Applied:

- Data Bars
- Icons
- Dynamic Background Colors

---

# 📱 Mobile Layout

Dashboard optimized for:

- Mobile devices
- Responsive KPI views

---

# 🔐 Security

Implemented:

- Row-Level Security (RLS)
- Role-based filtering

---

# 🛠 Tools & Technologies

- Power BI
- Power Query
- DAX
- Data Modeling
- Excel / CSV

---

# 📂 Project Structure

```text
📁 PowerBI-Student-Analytics
 ┣ 📄 README.md
 ┣ 📄 Student_Analytics.pbix
 ┣ 📁 Dataset
 ┃ ┣ 📄 Students.csv
 ┃ ┣ 📄 Scores.csv
 ┃ ┣ 📄 Attendance.csv
 ┃ ┗ 📄 Behavior.csv
```

---

# 📸 Dashboard Preview

(Add screenshots here)

---

# 📌 Key Learnings

- Data transformation using Power Query
- DAX calculations and KPIs
- Interactive dashboard design
- Data modeling using Star Schema
- Time intelligence functions
- Power BI storytelling

---

# 👨‍💻 Author

**Anupam vaishnav**

Power BI | Data Analytics | Dashboard Development

---

# ⭐ If you like this project

Give this repository a ⭐ on GitHub.
