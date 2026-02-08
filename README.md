# Power-BI-Projects
# 📊 Power BI Project Management Dashboard

## 🔍 Project Overview
This Power BI dashboard provides operational and performance insights for project and ticket management. It enables team managers to monitor ticket resolution trends, overdue work, workflow throughput, and short-term delivery performance.

The solution was built using automated REST API extraction from a SharePoint-based ticket system and supports daily refresh in Power BI Service.

---

## 🔄 ETL & Data Pipeline
- Data source: SharePoint List via REST API
- Extraction: API endpoint connected directly to Power BI
- Refresh: Scheduled daily refresh in Power BI Service
- Transformation:
  - Cleaned ticket status fields
  - Normalized workflow stages
  - Converted date fields for time intelligence analysis
  - Created calculated columns for SLA, overdue flags, and cycle time
- Modeling: Star schema with Date dimension and ticket fact table

---

## 🎯 Business Questions Answered
- How many tickets were solved in the past 7 days?
- How many projects or tickets are currently overdue?
- What is the weekly workflow throughput rate?
- Are resolution times improving or slowing down?
- Which teams or categories generate the highest ticket volume?
- What is the trend of open vs closed tickets over time?

---

## 📈 Key KPIs
- Tickets resolved (last 7 days)
- Overdue tickets count
- Average resolution time
- Workflow throughput per week
- Open vs closed ratio
- Tickets by status and priority

---

## 🧰 Tools & Techniques
- Power BI Desktop & Service
- REST API ingestion
- Power Query (M) transformations
- DAX time intelligence measures
- Scheduled refresh configuration
- KPI and SLA modeling

---

## 🖼️ Dashboard Preview
(Add screenshots in /screenshots and link here)

---

## 🧠 Skills Demonstrated
- API-based data ingestion
- Automated refresh pipelines
- Operational KPI design
- Time-based performance analytics
- Management-focused dashboard design

---
