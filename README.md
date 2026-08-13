## 📊 Integrated Humanitarian Response & MEAL Dashboard

A production-ready **Humanitarian Data Management & Monitoring/Evaluation (MEAL) Dashboard** built in Microsoft Excel. This case study demonstrates how to structure, process, clean, and visualize multi-donor humanitarian assistance data across various Ukrainian hromadas (communities).

---
## 🖼️ Visual Preview

![Humanitarian Response Dashboard](https://github.com/OlehRudyk/excel_dashboard_NGO/blob/main/dashboard_NGO.png)
> *Figure 1: Interactive Excel Dashboard featuring dynamic KPI cards, demographic breakdowns, regional coverage analysis, service type distributions, and cross-filtering slicers.*

---

## 📌 Executive Summary

Civil society and non-governmental organizations (NGOs) operating in complex humanitarian environments need transparent, real-time insights to track project progress, fulfill donor reporting requirements (e.g., USAID, UNICEF, UN Women), and optimize service delivery.

This project delivers an interactive Excel dashboard that tracks **1,000 beneficiary service cases** across 10 regions of Ukraine. It provides instant visibility into demographics, geographic reach, service streams, and participant satisfaction.

---

## 🔑 Key Features & Metrics

* **Dynamic KPI Cards:** Real-time tracking of overall beneficiary reach, targeted regions, active donor grants, and satisfaction scores (`AVERAGE`).
* **Demographic Breakdown:** Doughnut chart categorizing beneficiaries by age group (Girls 0–17, Women 18–49, Women 50+).
* **Geographic Coverage:** Sorted regional reach analysis highlighting key operational hubs (e.g., Kyivska, Dnipropetrovska).
* **Service Line Analysis:** Horizontal bar chart tracking primary interventions:
  * Psychosocial Support
  * GBV Protection & Counseling
  * Legal Assistance
  * Humanitarian / Hygiene Kits
  * SRHR & Educational Workshops
* **Vulnerable Group Categorization:** Breakdown by beneficiary status (IDPs, local community members, large families, military families).
* **Interactive Slicers:** Full cross-filtering by **Year**, **Month**, **Donor/Project**, **Service Type**, and **Region**.

---

## 🛠️ Data Architecture & Tech Stack

* **Tool:** Microsoft Excel (Power Query, Pivot Tables, Pivot Charts, Slicers, Formatted KPI Cards).
* **Dataset:** 1,000 synthetic records simulating field data collection via **KoboToolbox** (spanning 2025–2026).
* **Data Model Structure:**
  * `Raw_Data`: Relational table containing clean transactional service records.
  * `Pivot_Tables`: Aggregated data tables serving as data sources for charts.
  * `Dashboard`: Clean, gridless UI optimized for executive reporting and donor presentations.

---

## 💡 Key MEAL Insights Derived

1. **IDP Priority:** Over 45% of total assistance reached Internally Displaced Persons (IDPs), reflecting alignment with protection priorities.
2. **High Demand for Mental Health Services:** Psychosocial support and GBV consultations represent the largest service volume (~55% combined).
3. **Regional Distribution:** Kyivska and Dnipropetrovska oblasts showed the highest concentration of aid delivery, indicating high field team capacity in those hubs.
