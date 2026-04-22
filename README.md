# Wind Turbine Lifecycle Analytics Dashboard (Power BI)

Interactive Power BI prototype designed to monitor offshore wind turbine lifecycle performance, deviations, equipment health, and operational risks.

This project transforms manually maintained operational data into a decision-support dashboard using data modeling, DAX measures, KPI analytics, drill-through reporting, and interactive dashboard design.

The solution supports both management-level oversight and turbine-level operational analysis through:

- Portfolio performance monitoring  
- Project and turbine drill-through analysis  
- Equipment fault and risk analytics  
- Data-driven decision support  

---

## Problem Statement

Operational lifecycle data across offshore wind construction projects is often maintained manually by multiple stakeholders, creating challenges related to:

- Transparency  
- Consistency  
- Scalability  
- Performance monitoring  
- Early risk identification  

This project addresses those challenges through an interactive analytical prototype built in Power BI.

---

## Objectives

The dashboard is designed to support users in:

- Tracking turbine lifecycle progress  
- Monitoring durations and deviations  
- Analyzing operational patterns  
- Identifying risks and bottlenecks  
- Supporting data-driven decision-making  

---

## Technologies & Skills Used

- Power BI  
- DAX Measures  
- Relational Data Modeling  
- KPI Design & Analytics  
- Data Cleaning and Transformation  
- Interactive Dashboard UI Design  
- Drill-through Reporting  
- Risk & Performance Analysis  

---

## Data Model

The model is structured around:

- Projects  
- Turbines  
- Loadouts  
- Installation Records  
- Commissioning Records  
- Service Records  
- Equipment Health Data  
- Motion Sensor Data  

The model uses project-to-turbine relationships and lifecycle fact tables to support scalable filtering and analysis.

### Data Model View
![Data Model](images/data-model.png)

---

# Dashboard Pages

## 1. Portfolio Overview

High-level management view showing:

- Total Projects  
- Total Turbines  
- Total Lifecycle Hours  
- Deviations by Project  
- Hours by Lifecycle Phase  
- Portfolio-level performance insights  

![Portfolio Overview](images/portfolio-overview.png)

---

## 2. Project Details

Project-level analysis page including:

- Project-specific KPIs  
- Loadout duration analysis  
- Hours by lifecycle phase  
- Deviations by phase  
- Drill-through support to turbine-level detail  

![Project Details](images/project-details.png)

---

## 3. Turbine Details

Asset-level monitoring page showing:

- Installation, Commissioning, and Service Hours  
- Total Deviation per Turbine  
- Motion Sensor Status  
- Turbine-specific lifecycle insights  

![Turbine Details](images/turbine-details.png)

---

## 4. Equipment Health

Technical reliability monitoring page including:

- Equipment Fault Events  
- Failure Rate  
- Failure Type Distribution  
- Machine Type Analysis  
- Equipment Risk Indicators  

![Equipment Health](images/equipment-health.png)

---

## 5. Risk & Performance Insights

Decision-support page focused on:

- Total Deviations  
- Average Deviation per Turbine  
- Worst Performing Project  
- Highest Risk Lifecycle Stage  
- Top High-Risk Turbines  
- Hours vs Deviation Analysis  

![Risk & Performance](images\Risk & Performance.png)

---

# Key DAX Measures

Examples of business logic implemented through DAX:

## Total Lifecycle Hours
Aggregates installation, commissioning, and service hours.

## Deviation Total
Combines deviations across all lifecycle stages.

## Average Deviation per Turbine
Normalizes deviations across turbines for fair comparison.

## Worst Project
Ranks projects and identifies the highest-risk project.

## Highest Risk Stage
Identifies the lifecycle phase contributing most to deviations.

## Equipment Failure Rate
Measures proportion of equipment fault events.

---

## Business Value

This prototype supports:

- Performance monitoring across projects  
- Early risk identification  
- Lifecycle bottleneck detection  
- Equipment reliability analysis  
- Operational and management decision support  

---

## Example Business Questions Answered

This solution helps answer questions such as:

- How many turbines belong to each project?  
- Which lifecycle stage takes the longest?  
- Where are deviations highest?  
- Which projects are slower than expected?  
- Which turbines or loadouts are causing issues?  
- Can managers spot risk early?  

---

## Future Improvements

Possible extensions:

- Predictive maintenance using Python/ML  
- Automated anomaly detection  
- Real-time IoT sensor integration  
- Streaming data dashboards  
- Deployment as a full digital application  

---

## Repository Structure

```text
.
├── WindTurbineLifecycleDashboard.pbix
├── README.md
└── images/
    ├── data-model.png
    ├── portfolio-overview.png
    ├── project-details.png
    ├── turbine-details.png
    ├── equipment-health.png
    └── risk-performance.png
```

---

## About This Project

This project was developed as a digital solutions case study inspired by offshore wind construction operations and demonstrates how Power BI can be used not only for reporting, but for building an analytical decision-support prototype.