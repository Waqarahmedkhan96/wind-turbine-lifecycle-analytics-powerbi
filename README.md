# Wind Turbine Lifecycle Analytics Dashboard (Power BI)

## Overview

Interactive Power BI prototype designed to monitor offshore wind turbine lifecycle performance, deviations, equipment health, and operational risks.

This project transforms manually maintained operational data into a decision-support dashboard using data modeling, DAX measures, KPI analytics, drill-through reporting, and interactive dashboard design.

---

## Problem Statement

Operational lifecycle data across offshore wind construction projects is often fragmented across stakeholders, creating challenges related to:

- Transparency  
- Consistency  
- Scalability  
- Performance monitoring  
- Early risk identification  

This dashboard addresses those challenges through an interactive analytical prototype built in Power BI.

---

## Features

- Portfolio Overview KPIs  
- Project-level Drill-through Analysis  
- Turbine-level Monitoring  
- Equipment Fault Analytics  
- Risk & Performance Dashboard  
- Dynamic DAX KPIs  
- Interactive Slicers and Drill-through Navigation  

---

## Technologies Used

- Power BI  
- DAX  
- Data Modeling  
- KPI Design  
- Data Cleaning  
- Dashboard UI Design  
- Drill-through Reporting  
- Risk Analytics  

---

# Data Model

Relational model connecting:

- Projects  
- Turbines  
- Loadouts  
- Installation Records  
- Commissioning Records  
- Service Records  
- Equipment Health Data  
- Motion Sensor Data  

### Data Model View

![alt text](<Data Model.png>)

---

# Dashboard Pages

## Portfolio Overview

Management-level overview showing:

- Total Projects  
- Total Turbines  
- Total Lifecycle Hours  
- Deviations by Project  
- Hours by Lifecycle Phase  

![alt text](<Portfolio Overview.png>)

---

## Project Details

Detailed project-level analysis including:

- Project KPIs  
- Loadout Duration Analysis  
- Hours by Phase  
- Deviations by Phase  
- Drill-through to turbine detail  

![alt text](<Project Details.png>)

---

## Turbine Details

Asset-level turbine monitoring showing:

- Lifecycle Hours  
- Turbine Deviations  
- Motion Sensor Status  
- Turbine-specific insights  

![alt text](<Turbine Details.png>)

---

## Equipment Health

Equipment reliability monitoring including:

- Fault Events  
- Failure Rate  
- Failure Type Distribution  
- Machine Type Analysis  

![alt text](<Equipment Health.png>)

---

## Risk & Performance Insights

Decision-support page focused on:

- Total Deviations  
- Avg Deviation per Turbine  
- Worst Project  
- Highest Risk Stage  
- Top High-Risk Turbines  

![alt text](<Risk & Performance.png>)

---

# Key DAX Measures

## Total Lifecycle Hours

Combines installation, commissioning, and service hours into one total operational effort measure.

---

## Deviation Total

Aggregates deviations across all lifecycle stages to quantify performance gaps.

---

## Average Deviation per Turbine

Normalizes deviations across turbines for fair project comparison.

---

## Worst Project

Ranks projects and identifies the project with the highest deviation.

---

## Highest Risk Stage

Identifies the lifecycle stage contributing most to operational risk.

---

## Equipment Failure Rate

Calculates the proportion of equipment fault events.

---

## Business Value

Supports:

- Performance monitoring  
- Risk identification  
- Bottleneck detection  
- Fault analysis  
- Data-driven decision-making  

---

## Example Business Questions Answered

This solution helps answer:

- How many turbines belong to each project?  
- Which lifecycle stage takes the longest?  
- Where are deviations highest?  
- Which projects are slower than expected?  
- Which turbines or loadouts are causing issues?  
- Can managers spot risk early?  

---

## Future Improvements

Possible extensions:

- Predictive maintenance with Python  
- Automated anomaly detection  
- Real-time sensor streaming  
- IoT integration  
- Advanced forecasting models  

---

## Repository Structure

```text
.
├── WindTurbineLifecycleDashboard.pbix
├── README.md
├── Data Model.png
├── Portfolio Overview.png
├── Project Details.png
├── Turbine Details.png
├── Equipment Health.png
└── Risk & Performance.png
```

---

## About This Project

This project demonstrates how Power BI can be used not only for reporting, but for building an analytical decision-support prototype for offshore wind operations.