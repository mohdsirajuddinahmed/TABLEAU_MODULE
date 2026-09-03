# 🏥 Hospital Patient Analytics & Treatment Outcome Dashboards

**Author:** Mohd Sirajuddin Ahmed | Associate Data Scientist (In Training)

---

## 📌 Project Overview

Welcome to my Healthcare Analytics project! As an Associate Data Scientist currently developing my skills in visual analytics and business intelligence, I built this multi-tab dashboard to help healthcare management analyze clinical performance and operational costs across Andhra Pradesh and Telangana.

All interactive Tableau Public links, walkthrough video links, dashboard screenshots, and detailed business recommendations are embedded directly inside the attached PDF report.

---

## 📋 Business Scenario & Objectives

Healthcare organizations process high volumes of clinical and operational data. The objective of this project is to provide hospital leadership with actionable insights to optimize treatment costs, track patient recovery, and evaluate doctor/department performance.

### Key Objectives
* **Admission & Discharge Analysis:** Track admission trends over time across various departments.
* **Clinical Performance:** Measure key metrics including recovery rates, mortality rates, and average length of stay (LOS).
* **Cost Optimization:** Analyze average treatment costs relative to disease severity.
* **Interactive Dashboards:** Develop executive-level dashboards with custom filters, drill-downs, and KPIs.

---

## 🧮 Calculated Fields Implemented

* **Length of Stay (LOS):** `DATEDIFF('day', [Admission_Date], [Discharge_Date])`
* **Recovery Rate:** Percentage of patients with `Recovery_Status = 'Recovered'`
* **Mortality Rate:** Percentage of patients with `Recovery_Status = 'Expired'`
* **Average Treatment Cost:** `AVG([Treatment_Cost])`

---

## 📂 Repository Contents

* "Healthcare Tableau Project Assignment Mohd Sirajuddin Ahmed.pdf" — Complete project report featuring the scenario breakdown, key performance indicators, live Tableau Public access links, video walkthrough link, and actionable business insights.

---

Maintained by Mohd Sirajuddin Ahmed — B.Tech CSE Student & Data Science Aspirant.
