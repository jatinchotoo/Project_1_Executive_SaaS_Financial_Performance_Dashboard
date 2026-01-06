# 📊 Executive SaaS Financial Performance & Capital Governance Dashboard

## 🖼️ Executive Dashboard Snapshots

Recruiters and executives can immediately see **CFO-ready visuals**:

| Executive Overview | Revenue & Growth Analysis |
|------------------|--------------------------|
| ![Executive Summary](screenshots/Executive_summary.png) | ![Revenue Analysis](screenshots/Revenue_Analysis.png) |

| Capital Ratios & Risk | Benchmark / Hurdle-Rate Accountability |
|---------------------|--------------------------------------|
| ![Ratios Overview](screenshots/Ratios_Overview.png) | ![Benchmark Dashboard](screenshots/Benchmark_Dashboard.png) |

| Comparative Entity Performance |
|-------------------------------|
| ![Comparative Dashboard](screenshots/Comparative_Dashboard.png) |

*All dashboards are taken directly from the Power BI PBIX file. These visuals demonstrate governance, capital discipline, and entity-level decision support.*

---

## Executive Thesis

In an environment of constrained capital and permanent accountability, executive finance teams require more than descriptive reporting. They require **decision-grade performance governance**.

This project delivers a **CFO-oriented Power BI dashboard** that consolidates fragmented SaaS billing and general ledger data into **capital allocation, risk, and performance signals** suitable for senior leadership and board-level oversight.

The platform is designed to support **capital stewardship, return discipline, and entity-level accountability**, rather than exploratory or experimental analytics.

---

## Business Context & Problem Statement

SaaS and multi-entity organisations frequently face:

- Fragmented financial and billing data across systems  
- Manual reconciliation during reporting and close cycles  
- Limited visibility into **capital efficiency**, not just revenue growth  
- Inconsistent benchmarking across subsidiaries  

These conditions impair timely decision-making and weaken capital discipline.

The objective of this project was to **centralise financial performance data**, **standardise executive metrics**, and **enable governed, repeatable performance oversight** through a single analytical platform.

---

## Solution Overview

A structured Power BI solution was developed to serve as an **executive performance and capital governance layer**.

Key components include:

- Normalised financial and billing datasets using Power Query (M)  
- A star-schema data model optimised for auditability and DAX performance  
- Custom DAX measures focused on growth quality, capital efficiency, and risk  
- Executive dashboards designed for CFO, ExCo, and board review  

The solution prioritises **clarity, control, and trust**, not technical novelty.

---

## Strategic Decision Support

This platform enables senior leadership to:

- **Assess Growth Quality**  
  Distinguish between headline revenue growth and economically sustainable MRR / ARR performance.

- **Enforce Capital Discipline**  
  Benchmark entity-level Return on Equity (ROE) against an internal **15% hurdle rate**.

- **Identify Emerging Risk**  
  Apply traffic-light logic to flag underperforming or deteriorating entities early.

- **Evaluate Capital Structure Efficiency**  
  Monitor leverage, liquidity, and debt utilisation across subsidiaries.

---

## Executive Intelligence Layers

### 1️⃣ Executive Performance Overview (CFO View)

High-level KPIs focused on:

- Revenue velocity and margin sustainability  
- Capital efficiency indicators  
- Consolidated risk signals  

*Decision enabled:*  
**Is current performance protecting or eroding shareholder value?**

*(See: `screenshots/Executive_summary.png`)*

---

### 2️⃣ Revenue & Unit Economics Analysis

Subscription-focused analytics covering:

- MRR / ARR trends  
- Retention tiers  
- Billing cycle distribution  

*Decision enabled:*  
**Which revenue streams justify continued investment?**

*(See: `screenshots/Revenue_Analysis.png`)*

---

### 3️⃣ Capital Efficiency & Risk Benchmarking

Side-by-side entity comparison of:

- Return on Equity (ROE)  
- Debt-to-Equity ratios  
- Liquidity and leverage efficiency  

*Decision enabled:*  
**Where is capital underperforming or over-leveraged?**

*(See: `screenshots/Ratios_Overview.png`)*

---

### 4️⃣ Hurdle-Rate Accountability

Gauge-based benchmarking against internal ROE targets.

*Decision enabled:*  
**Which entities require intervention, restructuring, or capital reallocation?**

*(See: `screenshots/Benchmark_Dashboard.png`)*

---

### 5️⃣ Comparative Entity Performance

Direct side-by-side comparison of entity-level KPIs to identify underperformance.

*(See: `screenshots/Comparative_Dashboard.png`)*

---

## Tools & Methodologies

- **Power BI** – data modeling, DAX measures, executive dashboards  
- **Power Query (M)** – data transformation and normalization  
- **Excel** – data preparation, reconciliation, and validation  
- **SQL-based queries** – structured data extraction  
- **Manual validation procedures** – accuracy and consistency checks  

This reflects a **finance-led analytics workflow**, not a software engineering or machine learning pipeline.

---

## Validation & Accuracy

To ensure reliability and governance:

- Key metrics were reconciled against source financial data  
- Ratio calculations were independently cross-checked  
- Outputs were manually reviewed for consistency and completeness  

The intent was to produce **audit-defensible executive reporting**, suitable for real-world finance environments.

---

## Repository Structure

```text
Project_1_Executive_SaaS_Financial_Performance_Dashboard/
├─ Data/
│  ├─ Financial_Ratios_Reference.csv.xlsx
│  └─ Financial_Raw_Data.csv.xlsx
├─ screenshots/
│  ├─ Executive_summary.png
│  ├─ Revenue_Analysis.png
│  ├─ Ratios_Overview.png
│  ├─ Benchmark_Dashboard.png
│  └─ Comparative_Dashboard.png
├─ scripts/
│  └─ measures.dax
├─ Project1-Dashboard.pbix
└─ README.md
```

---

## Professional & Industry Alignment

This project aligns directly with:

- Corporate FP&A and Group Finance teams  
- CFO Office and Finance Transformation roles  
- Multi-entity and SaaS organisations  
- Capital allocation and performance governance mandates  

**Relevant roles:**  
Senior FP&A Analyst · Strategic Finance Manager · Finance Transformation Lead · CFO Office Analyst · Decision Intelligence Analyst

---

## Scope Clarification

This project **explicitly excludes**:

- Forecasting or predictive modeling  
- Advanced machine learning or AI systems  
- Agentic or autonomous decision engines  
- Conceptual roadmaps or future-state claims  

It represents a **completed, production-style executive performance solution** focused on capital discipline and decision support.

---

## Closing Statement

This project demonstrates a **disciplined, CFO-grade approach to financial performance governance**, emphasizing accountability, capital efficiency, and executive decision clarity over technical excess.
