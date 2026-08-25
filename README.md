# 📊 EdTech & Telecom Sales & Counselor Performance Dashboard

> **🚀 LIVE INTERACTIVE POWER BI DASHBOARD:** 
> Explore the fully interactive report right in your browser: 
> 👉 **[Click Here to Access Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNjhkYjQxNWItYmZlZS00M2UwLTk3MzAtYjkxYWNkNDdhMTY5IiwidCI6IjY2ZGNhNGQyLTU0ZDktNDhiOC1hZDFhLTliOWUwNmRiMGQ5MCJ9)**

---

An end-to-end Power BI dashboard built for an educational consultancy and telecommunications client — tracking lead conversion pipelines, telecommunication activity metrics, and counselor efficiency across 3 executive-facing pages.

> This project was built independently by me. The synthetic source datasets (branches, counselors, leads CRM, and telecom call logs) were structured to simulate realistic sales operations data — all modeling, data cleaning, Power Query transformations, DAX, and dashboard design were done by me in Power BI.

---

## 📌 Project Overview

This project simulates a real-world EdTech analytics environment: raw, messy operational data is transformed through Power Query into a clean relational model, then visualized in Power BI to answer the questions managers and team leads ask every week.

**Business questions answered:**
- Are we hitting our enrollment and lead conversion targets by branch and counselor?
- What are the primary reasons leads drop or turn to "Not Interested," and how do they trend over time?
- Are we maintaining high outreach efficiency through connected call volumes and follow-up tracking?
- How is lead acquisition trending, and which study destinations or courses drive the highest interest?

All pages share global consistency across filters and slicers for seamless cross-reporting.

---

## 📄 Dashboard Pages

### 1. Sales Overview
A weekly exception report for leadership — one glance shows total leads, dropped leads, not-interested counts, pending leads, and enrolled leads with period-over-period performance comparisons, alongside branch/counselor breakdowns.

<img src="image/Sales%20Overview.png" alt="Sales Overview">

### 2. Activity Log
Breaks down operational outreach efficiency — tracking daily dialing volumes, connection ratios, unique lead reach, and visual preference charts for regional study destinations.

<img src="image/Activity%20Log.png" alt="Activity Log">

### 3. Follow-Up Log (Master Matrix)
Focused on student pipeline audits — an operational matrix combining lead IDs, counselor mappings, student names, target exams (IELTS, GRE, PTE, TOEFL), and milestone tracking with custom status tags and CRM remarks.

<img src="image/Follow-Up%20Log.png" alt="Follow-Up Log">

---

## 🧱 Data Model & Architecture

Key modeling and transformation highlights:
- **Data Cleansing:** Raw text keys, mixed formats, and uncleaned fields standardized in Power Query before modeling.
- **Relational Structure:** Tables structured to handle multi-level dimensions (branches, counselors, leads, and telecom logs).

---

## 🛠️ Tech Stack

- **Power BI Desktop** — data modeling, DAX measures, report design
- **Power Query (M)** — data ingestion, cleansing, text processing, and conditional error handling
- **DAX** — custom measures covering time intelligence, dynamic status states, and conversion metrics

---

## 🗂️ Repository Structure

```text
EdTech-Sales-Counselor-Performance-Dashboard/
├── README.md
├── EdTech Dashboard Demo 2.pbix
├── RawFiles/
│   ├── branches_master.csv
│   ├── counselors_master.csv
│   ├── leads_crm_enriched.csv
│   └── telecom_call_logs_enriched.csv
└── image/
    ├── Sales Overview.png
    ├── Activity Log.png
    └── Follow-Up Log.png
