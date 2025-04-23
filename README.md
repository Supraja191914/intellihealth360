# IntelliHealth360: Unified Healthcare Insights with AI + Microsoft Fabric

## 📘 Project Overview
IntelliHealth360 is a full-scale, end-to-end healthcare analytics platform built entirely on the Microsoft Fabric free-tier and Azure ecosystem. It brings together real-time insights on patient risk, medication adherence, hospital resource utilization, and claims performance using synthetic healthcare data — enriched with GenAI capabilities for natural language querying.

## 🚀 Key Objectives
- Provide a unified data view across multiple healthcare domains
- Enable low-code ingestion, transformation, and visualization
- Demonstrate real-world Azure Data Engineering skills
- Integrate GenAI (Power BI Q&A) for intuitive insight access

## 🧰 Tools & Tech Stack
- **Microsoft Fabric**: Dataflow Gen2, Lakehouse, SQL Endpoint
- **Azure**: Storage, OpenAI (optional)
- **Power BI**: Data modeling, visualizations, Q&A
- **GitHub**: Version control, CI/CD (optional simulation)
- **Dataset**: Synthea synthetic EHR data (CSV)
  
## 🧠 IntelliHealth360: Unified Healthcare Insights with AI + Fabric

This project uses Microsoft Fabric to ingest, transform, and visualize synthetic healthcare data using OneLake, Lakehouse, and Power BI.

### 🧱 Architecture Overview

![IntelliHealth360 Architecture](./docs/intellihealth360.png)




## 🧱 Architecture
```
[Synthea CSVs] --> [Fabric Dataflow Gen2] --> [Fabric Lakehouse] --> [SQL Endpoint]
                                                        ↓                          ↓
                                        [Power BI Dataset]     [Power BI Dashboard + Q&A]
```

## 📊 Key Features
- Chronic Disease Risk Scoring (diabetes, hypertension)
- Medication Adherence Summary
- Claims Approval Rate & Timelines
- Hospital Resource Forecasting (admissions)
- Region-based Geo Map & Slicers
- Power BI Q&A (GenAI-driven querying)

## 📂 Folder Structure
```
/intellihealth360
├── data/                  # Synthea CSVs
├── lakehouse/             # SQL scripts and views
├── pbix/                  # Power BI report (if exported)
├── assets/                # Dashboard screenshots
├── docs/
│   ├── architecture.png   # System diagram
│   └── feature_cards.md   # Use case deep dives
└── README.md              # Project overview
```

## 📁 Dataset
Synthea sample files:
- patients.csv
- encounters.csv
- conditions.csv
- medications.csv
- claims.csv

All stored in Microsoft Fabric Lakehouse using Dataflow Gen2.

## ✅ Highlights
- 100% Free-tier compatible
- Real-world data transformations in SQL
- No-code/low-code ingestion pipeline
- Power BI dashboard with GenAI search
- Resume-ready and publicly shareable

## 🔗 Publish & Share
- Public Power BI report: [Add Link Here]
- GitHub Repo: [Add Repo URL Here]
- LinkedIn Showcase Post: [Write Post → Include Metrics, Screenshot, Repo]

---


