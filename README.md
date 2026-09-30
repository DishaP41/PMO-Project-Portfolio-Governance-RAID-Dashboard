# PMO Project Portfolio Governance & RAID Dashboard

A portfolio project demonstrating **Project Management Office (PMO) governance, project health monitoring, RAID management, milestone tracking, financial variance analysis, and executive reporting** using **Tableau and Excel**.

> **Note:** This project uses a synthetic dataset created specifically for portfolio and analytics demonstration purposes.

## Project Overview

Managing multiple projects requires clear visibility into delivery status, risks, issues, dependencies, milestones, ownership, and financial performance.

This project simulates a PMO environment where project information is consolidated into a structured portfolio reporting framework. The objective is to help project managers and leadership quickly identify projects requiring attention, monitor RAID items, track delivery progress, and support governance decisions.

The portfolio contains:

- **18 projects**
- **60 RAID records**
- Multiple business workstreams
- Project milestones and ownership information
- Budget and actual-spend data
- Project health and completion metrics

## Business Objectives

The project was designed to answer key PMO questions such as:

- How many projects are currently On Track, At Risk, Delayed, or Completed?
- Which projects require immediate management attention?
- What are the major open Risks, Issues, Assumptions, and Dependencies?
- Which critical RAID items remain unresolved?
- Which milestones or governance actions are overdue?
- How is project delivery progressing across different workstreams?
- Which projects are experiencing budget variance?
- Where should PMO leadership focus escalation and follow-up efforts?

## Dashboard KPIs

The dashboard tracks key portfolio and governance indicators including:

| KPI | Purpose |
| --- | --- |
| Total Projects | Overall portfolio size |
| On Track Projects | Projects progressing according to plan |
| At Risk / Delayed Projects | Projects requiring additional attention |
| Average Completion % | Overall delivery progress |
| Open RAID Items | Outstanding governance items |
| Critical RAID Items | High-priority risks/issues requiring escalation |
| Overdue Items | RAID items or milestones past their target date |
| Budget Variance % | Difference between planned budget and actual spend |

## RAID Management

The project uses the **RAID framework** to structure project governance.

**R — Risks:** Potential events that may negatively affect project delivery.

**A — Assumptions:** Conditions assumed to be true during project planning.

**I — Issues:** Existing problems requiring resolution or escalation.

**D — Dependencies:** Activities or deliverables dependent on other teams, projects, or events.

Each RAID record includes:

- RAID ID
- Project ID
- RAID Type
- Severity
- Status
- Opened Date
- Due Date
- Owner
- Description

This structure enables PMO teams to monitor outstanding items and identify areas requiring escalation.

## Portfolio Analysis

### Project Health Monitoring

Projects are classified into:

- On Track
- At Risk
- Delayed
- Completed

This provides leadership with a quick portfolio-level view of delivery health.

### Risk & Issue Monitoring

RAID items are analyzed by:

- Severity
- Status
- Project
- Owner
- Due date
- RAID category

Critical and unresolved items can be highlighted for governance review and escalation.

### Milestone Tracking

Project milestones are tracked using:

- Planned Date
- Actual Date
- Milestone Status
- Project Owner

This helps identify delayed milestones and schedule exceptions.

### Financial Monitoring

Each project contains:

- Planned Budget
- Actual Spend
- Budget Variance %

Budget variance enables identification of projects where actual spending is above or below the approved project budget.

## Tableau Dashboard

The interactive Tableau dashboard is designed as an **Executive PMO Portfolio View**.

### Dashboard Components

**KPI Cards**

Total Projects | On Track | At Risk / Delayed | Open RAID | Critical RAID | Average Completion | Budget Variance

**Project Health**

Visual comparison of projects by delivery status.

**RAID Severity Analysis**

Open RAID items categorized by severity to highlight areas requiring management attention.

**Workstream Portfolio**

Comparison of project volume and delivery progress across business workstreams.

**Project Risk View**

Detailed view of At Risk and Delayed projects with completion percentage, priority, and financial variance.

**RAID Detail**

Detailed governance table showing open RAID items, owners, severity, due dates, and current status.

### Interactive Filters

The dashboard supports filtering by:

- Workstream
- Project Manager
- Project Status
- Priority

These filters allow stakeholders to move from portfolio-level reporting to individual project-level analysis.

## Tableau Public Dashboard

**Interactive Dashboard:** [Tableau Public Link]

*The Tableau Public link will be added after the dashboard is published.*

## Data Structure

### Projects

Contains portfolio-level information including:

- Project ID
- Project Name
- Workstream
- Project Manager
- Sponsor Function
- Start Date
- End Date
- Project Status
- Priority
- Completion %
- Budget
- Actual Spend
- Budget Variance %

### RAID Log

Contains project governance records including risks, assumptions, issues, and dependencies.

### Milestones

Contains planned and actual milestone dates, milestone status, and ownership information.

## Tools & Skills Demonstrated

**Project Management / PMO**

Project Governance • Portfolio Monitoring • RAID Management • Milestone Tracking • Risk & Issue Tracking • Dependency Tracking • Status Reporting • Executive Reporting • Project Performance Monitoring

**Tableau**

Interactive Dashboards • KPI Reporting • Calculated Fields • Filters • Dashboard Actions • Data Visualization

**Microsoft Excel**

Project Tracking • Structured Data Management • Portfolio Reporting • Data Validation • Governance Reporting

**Analytics**

Project Health Analysis • Budget Variance Analysis • Exception Reporting • Trend Monitoring • Performance Analysis

## Repository Structure

```text
PMO-Project-Portfolio-Governance-RAID-Dashboard/
│
├── PMO_Project_Portfolio_Governance_RAID.xlsx
├── PMO_Tableau_Flat_Data.csv
└── README.md
```

## Key Takeaways

This project demonstrates how structured PMO reporting can transform individual project updates into a consolidated portfolio view.

By combining project health, RAID items, milestones, ownership, and financial information, the dashboard enables stakeholders to identify delivery exceptions, prioritize risks and issues, monitor portfolio performance, and support structured governance discussions.

## Author

**Disha Pramanick**

Data Analytics | Business Reporting | Project Management & PMO Analytics

[LinkedIn](https://www.linkedin.com/in/disha-pramanick-96545a380/) | [Portfolio](https://dishapramanick2018-eng.github.io/)
