# CROSS-CHANNEL MARKETING INTELLIGENCE

### MULTI-CHANNEL ATTRIBUTION · STAR SCHEMA ARCHITECTURE · CAPITAL REALLOCATION

**Turning high-volume cross-channel marketing telemetry into disciplined capital allocation decisions.**

[![Power BI](https://img.shields.io/badge/POWER%20BI-STAR%20SCHEMA%20%26%20BI-F2C811?logo=powerbi&logoColor=black)](https://github.com/prospernwaiwu/improvado-marketing-analytics)
[![DAX](https://img.shields.io/badge/DAX-TIME%20INTELLIGENCE%20%26%20KPIs-0078D4?logo=microsoft&logoColor=white)](https://github.com/prospernwaiwu/improvado-marketing-analytics)
[![Python](https://img.shields.io/badge/PYTHON-DATA%20ENGINEERING-3776AB?logo=python&logoColor=white)](https://github.com/prospernwaiwu/improvado-marketing-analytics)

---

## EXECUTIVE SUMMARY

Paid media organizations rarely fail for lack of raw platform numbers; they fail when fragmented reporting masks where marginal capital actually generates return. Across **181M+ impressions** and a 12-month operating window spanning **Programmatic**, **Paid Search**, and **Paid Social**, this project establishes a clean analytical foundation that separates upper-funnel scale from high-intent click efficiency and turns channel diagnostics into concrete budget reallocation priorities.

---

## EXECUTIVE DASHBOARD

### 01 — Cross-Channel Marketing Executive Summary

![Cross-Channel Marketing Executive Summary](Screenshot%20(78).png)

A consolidated executive reporting canvas uniting top-level KPIs, month-over-month (MoM) variance indicators with inline sparklines, 12-month impression pacing, interactive global slicers (`Date`, `Data Source`, `Channel`, `Campaign`), and multi-grain performance tables across **Channel**, **Data Source**, and **Campaign**.

---

## ANALYTICAL MANDATE & SCOPE

The analytical architecture is built to answer five commercial and operational questions:

1. **Pacing & Trajectory:** How do impressions, spend, and engagement shift month-over-month across the 12-month operating period?
2. **Scale vs. Efficiency:** Which channels operate as broad top-of-funnel reach engines versus high-intent efficiency drivers?
3. **Granular Attribution:** Where do performance divergences appear across channels, data connectors, and individual campaigns?
4. **Capital Drag:** Which segments lag portfolio benchmarks in reach scale or month-over-month momentum?
5. **Reallocation Discipline:** Where should incremental spend shift to improve efficiency without inflating total budget?

**Scope & Dimensional Coverage**
* **181M+ total impressions** evaluated over a 12-month reporting horizon.
* **Three core channels:** Programmatic, Paid Search, and Paid Social.
* **Three reporting grains:** Channel, Data Source, and Campaign.
* **Interactive filtering:** Global slicers for Date, Data Source, Channel, and Campaign.

---

## ARCHITECTURE & ENGINEERING WORKFLOW

### 01. Data Engineering & Standardization — Python
Engineered a repeatable data-preparation workflow that normalizes multi-channel marketing records, enforces consistent calendar and channel taxonomies, and prepares clean analytical tables for downstream semantic modeling.

### 02. Star Schema Semantic Model — Power BI
Designed a dimensional model separating high-volume metric records from descriptive lookup tables so slicers and drill-downs behave predictably without circular relationships or ambiguous filter paths:
* `Fact_Marketing_Performance` — Core impression, click, spend, and conversion records across the 12-month operating period.
* `Dim_Date` — Calendar dimension supporting time-intelligence and monthly pacing analysis.
* `Dim_Channel` — Top-level channel classifications (`Programmatic`, `Paid Search`, `Paid Social`).
* `Dim_Data_Source` — Upstream marketing connectors and source systems.
* `Dim_Campaign` — Campaign-level attributes for granular performance and variance analysis.

### 03. DAX Measures & Reporting Layer
Built DAX measures powering funnel aggregations, click-through rate (CTR), month-over-month variances, and inline sparklines across **8 Executive KPI Cards**, a **12-Month Impression Trend** view, and **Channel / Data Source / Campaign** tables—allowing stakeholders to move from macro summaries to specific campaign movement without rebuilding visuals.

---

## KEY FINDINGS

| Channel | Funnel Role | Key Signal | Commercial Takeaway |
|---|---|---|---|
| **Programmatic** | Reach & scale engine | **91M+ impressions** (>50% of 181M+ total volume) | Anchors broad top-of-funnel visibility across the reporting period |
| **Paid Search** | High-intent efficiency leader | **9.36% CTR** | Delivers strongest click engagement and intent per impression |
| **Paid Social** | Underperforming segment | Trails in scale and MoM momentum | Represents capital drag requiring audit before budget expansion |

* **Scale Concentration:** Programmatic accounts for **91M+ of the 181M+ total impressions**, serving as the primary upper-funnel reach engine.
* **Efficiency Leadership:** Paid Search leads engagement at **9.36% CTR**, demonstrating stronger intent relative to competing channels.
* **Momentum Gap:** Paid Social lags behind in both impression volume and month-over-month momentum, exposing an efficiency gap relative to top-performing search inventory.

---

## CAPITAL ALLOCATION RECOMMENDATIONS

1. **Reallocate Incremental Spend Toward High-Intent Paid Search:** Shift marginal budget from lagging Paid Social campaigns into high-intent Paid Search connectors (including **Google Search Ads 360**) to capture stronger intent and improve overall efficiency without raising total spend.
2. **Preserve Core Programmatic Reach:** Maintain baseline funding for Programmatic (**91M+ impressions**) so upper-funnel reach and brand awareness remain intact while trimming lower-return spend elsewhere.
3. **Enforce Performance Discipline on Paid Social:** Audit audience targeting, creative assets, and pacing on underperforming Paid Social campaigns before approving additional budget allocation.

---

## DELIVERABLES

* **Power BI Model & Report (`.pbix`):** Complete Star Schema model, DAX measures, and executive dashboard.
* **Executive Exports (`.pdf` & `.png`):** Static report export and visual capture of the reporting view.
* **Walkthrough & Live Access:** Executive video walkthrough and live dashboard link.

---

## DATA PROVENANCE & METHODOLOGY NOTE

This project uses a simulated/synthetic 12-month multi-channel marketing dataset structured to reflect realistic paid-media dynamics across Programmatic, Paid Search, and Paid Social channels for portfolio demonstration of data preparation, Star Schema modeling, DAX calculations, and executive BI reporting. Metrics and campaign entries are illustrative and do not represent live proprietary client data.

---

## AUTHOR & CONTACT

**Prosper Nwaiwu**  
Data & Business Intelligence Analyst

* **GitHub:** [github.com/prospernwaiwu](https://github.com/prospernwaiwu)
* **LinkedIn:** [linkedin.com/in/prosper-nwaiwu](https://www.linkedin.com/in/prosper-nwaiwu/)
