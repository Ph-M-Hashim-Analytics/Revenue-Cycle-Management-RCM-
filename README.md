# Smart Revenue Cycle Management (RCM) Optimization
## Financial Gap Remediation & Revenue Leakage Analytics at Elite Gulf Specialist Hospital

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data_Analysis_Expressions-blue?style=for-the-badge)
![Healthcare Analytics](https://img.shields.io/badge/Industry-Healthcare_Informatics-red?style=for-the-badge)

---

## 📌 Project Overview
This project focuses on resolving severe cash flow challenges and bridging the expanding gap between billed claims and actual collections for **Elite Gulf Specialist Hospital** (a premier 300-bed referral facility). Facing a staggering **66.73% denial rate**, the hospital's operational sustainability was threatened.

By engineering a robust, **4-page Business Intelligence (BI) application** built on a normalized **Star Schema data model**, this analysis successfully uncovered **$17.66 Million in total revenue leakage** and established a clear data-driven roadmap toward financial recovery.

### 🔗 Project Links
* **Full Case Study Article:** [Read the Detailed Article on Medium](https://medium.com/@esthyqn8/building-a-healthcare-analytics-dashboard-in-power-bi-55-000-patient-records-analyzed-6d85e5f660e6)
* **Interactive Dashboard:** [Explore the Live Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiNjYwODEyMDktZjdjMi00MTg5LWJiZTUtMDNhZTY0NDZhY2RhIiwidCI6IjAwMGUwNGNmLTllYjEtNGE3Mi1hZGU4LWZkZGJjNDA4NWJhOSJ9)

---

## 🎯 Project Objectives
1. **Root Cause Analysis:** Identify and isolate the core operational and administrative drivers behind high claim denial rates.
2. **AR Aging & Liquidity Tracking:** Analyze the maturity structure of accounts receivable to minimize bad debt exposure.
3. **Payer Performance Evaluation:** Benchmark insurance company behaviors (Bupa, Malath, Tawuniya) to optimize submission cycle efficiency.
4. **Targeted Impact:** Achieve a **25% reduction in denial rates** within the next quarter and accelerate cash collection loops.

---

## 📊 Core Analytical Pillars

### 1. Executive Revenue Analysis
* Direct contrast of macro-financial KPIs: **Gross Revenue ($26.47M)** vs. **Gross Losses ($17.66M)**.
* Identifies a critical **Net Collection Rate of 33.37%**, significantly lagging behind the 95.00% global healthcare standard.
* Pinpoints departmental underperformance where losses eclipse collections (Pharmacy, Inpatient, Radiology, and Lab).

### 2. Leakage Analysis & Root Cause Diagnosis
* Highlights **"Authorization Required"** as the leading cause of billing leakage, independently costing **$2.08M**.
* Identifies **"Eligibility Errors" ($1.19M)** and **"Coding Errors" ($1.12M)** as primary administrative bottlenecks.
* Exposes **Pharmacy ($4.45M)** and **Laboratory ($4.39M)** as the most critical revenue leakage hotspots.

### 3. AR Aging & Bad Debt Risks
* Measures a surged **Days Sales Outstanding (DSO) of 92 days** (industry ideal: 45 days).
* Shows a dropped **Collection Efficiency Index (CEI) of 35.30%**.
* Isolates high-risk zones, such as Bupa’s 2025 metrics, where **51.92% ($790.57K)** of outstanding debt resides in the critical >91-day bracket.

### 4. Payer Performance & Submission Cycle Efficiency
* Tracks the claim lifecycles of **997 total claims**, recording a **70.51% Clean Claim Rate** (703 clean claims).
* Analyzes the operational overhead of **294 reworked claims**, visually demonstrating diminishing returns past the 1st submission round.

---

## 🛠️ Data Engineering & Custom DAX Measures
The solution is backed by an optimized **Star Schema model** and **35 custom DAX measures** built for rapid, dynamic multi-dimensional slicing. Below are 10 core calculations utilized in the model:

| Measure Name | Description | Key Metric / Purpose |
| :--- | :--- | :--- |
| `DSO` | Days Sales Outstanding | Calculates average collection days |
| `Bad Debt Risk %` | Bad Debt Risk Percentage | Quantifies financial exposure of aged accounts |
| `AR Turnover Ratio` | Accounts Receivable Turnover | Evaluates collection velocity efficiency |
| `Clean Claims Count` | Clean Claims Volume | Counts claims accepted on first pass |
| `First Pass Yield %` | First Pass Yield Rate | Tracks baseline entry-level billing quality |
| `Aged Loss > 90 Days` | High-Risk Aged Loss | Pinpoints stagnating receivables over 90 days |
| `CEI %` | Collection Efficiency Index | Measures true cash captured vs. available funds |
| `Potential Recovery` | Salvageable Denied Value | Quantifies the value of high-probability recovery claims |
| `Denial Rate per Payer %` | Dynamic Payer Denial Rate | Breaks down specific rejection rates per insurer |
| `Net Collection Rate %` | Ultimate Financial Health KPI | Measures net billing vs. cash collected |

---

## 🚀 Strategic Recommendations
Based on the dashboard insights, three board-level recommendations were delivered to executive leadership:
1. **Automate Pre-Authorization (Pre-Auth) Gateways:** Integrate EHR system workflows directly with insurance portals to systematically prevent medication/lab dispensing prior to obtaining digital clearance tokens.
2. **Targeted Clinical Workshops:** Implement focused training for Pharmacy and Lab administrative/clinical staff to remediate documentation, eligibility, and coding errors before billing.
3. **Payer SLA Reviews:** Enforce strict contractual adjudication timelines with lagging insurers during quarterly reviews, backed by the empirical performance data from this model.

---

## 📬 Contact & Connect
* **LinkedIn:** [Mohamed Hashim on LinkedIn](https://www.linkedin.com/in/mohamed-hashim-ibrahim-/)
