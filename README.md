# 📊 Employee Presence Insight Dashboard

**HR Analytics | Attendance Intelligence | Power BI Project**

---

## 🚀 Project Summary

The **Employee Presence Insight Dashboard** is an end-to-end HR analytics solution built using **Power BI** to monitor employee attendance patterns, work-from-home trends, and sick leave behavior.

This project demonstrates:

* 📌 Data cleaning & transformation
* 📊 KPI design & DAX calculations
* 📈 Time-series trend analysis
* 📅 Day-of-week behavioral insights
* 📉 Workforce performance monitoring

---

## 🎯 Business Problem

HR teams often struggle to:

* Monitor attendance trends across employees
* Measure hybrid work (WFH) adoption
* Detect abnormal sick leave patterns
* Track workforce productivity over time

This dashboard provides a **centralized, interactive solution** for data-driven HR decision-making.

---

## 🧾 Dataset Overview

The dataset contains employee-level attendance records including:

* Employee Name
* Attendance Status *(P, WFH, SL, LWP)*
* Date
* Year / Quarter / Month / Day

---

## 🔄 Data Preparation Steps

* Cleaned and standardized attendance codes
* Created date hierarchy columns
* Built KPI measures using DAX
* Aggregated employee-level metrics
* Developed trend and comparative visuals

---

## 📊 Key KPIs Built (DAX Measures)

* **Total Working Days**
* **Present Days**
* **Presence %**
* **WFH %**
* **Sick Leave %**

### Example DAX Logic

```DAX
Presence % =
DIVIDE([Present Days], [Total Working Days]) * 100
```

---

## 📈 Dashboard Features
<img src="https://github.com/rasod-narasingha/HR-Data-Analysis/blob/main/retail_dashboard.png.png" width="900">

### 1️⃣ Executive KPI Overview

* Overall Presence: **91.83%**
* WFH Rate: **10.00%**
* Sick Leave Rate: **1.10%**
* Total Working Days: **4,369**

---

### 2️⃣ Employee-Level Performance

* Individual attendance comparison
* Identification of low-attendance employees
* Hybrid work distribution insights

---

### 3️⃣ Time Series Trend Analysis

* Presence % by Date
* WFH % by Date
* SL % by Date
* Trend lines to identify performance direction

---

### 4️⃣ Behavioral Insights (Day-of-Week)

* Highest attendance day: **Monday (93.21%)**
* Highest WFH day: **Friday (13.01%)**
* Highest SL day: **Tuesday (1.62%)**

These patterns highlight hybrid work preferences and weekday productivity shifts.

---

## 🛠 Tools & Skills Demonstrated

### Tools

* Power BI Desktop
* Microsoft Excel

### Technical Skills

* Data Cleaning & Transformation
* Data Modeling
* DAX Calculations
* KPI Development
* Time-Series Analysis
* Dashboard Design
* Business Insight Generation

---

## 📊 Analytical Insights

* Attendance remained stable above **90%** across the quarter.
* WFH spikes observed near the end of May.
* Sick leave increased slightly toward June.
* Fridays show significantly higher remote work behavior.
* Some employees demonstrate significantly lower presence rates — potential HR intervention candidates.

---

## 💼 Business Value

This dashboard enables HR teams to:

✔ Monitor workforce engagement
✔ Optimize hybrid work policies
✔ Detect absenteeism risks early
✔ Improve workforce planning
✔ Support performance evaluations with data

---

## 🔮 Future Enhancements

* Department-level breakdown
* Year-over-year comparison
* Predictive absenteeism modeling
* HRMS system integration
* Power BI Service deployment with automated refresh

---

## 👨‍💻 About This Project

This project was developed as part of a **Data Analytics portfolio** to demonstrate real-world HR analytics capabilities using Power BI.

It highlights practical business problem-solving, KPI engineering, and insight-driven storytelling.

---

## 👤 Author

**Rasod Narasingha**
Data Analyst | BI Developer | AI Enthusiast

---
