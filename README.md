# Telangana Tourism Analysis 🏛️

![Telangana Tourism Analysis](./assets/telangana-tourism-cover.png)

## 📌 Introduction / Problem Statement

Telangana is home to iconic landmarks such as the **Charminar**, **Ramoji Film City**, forts like **Qutb Shahi Tombs**, scenic hills, and natural waterfalls — making it one of South India's most diverse tourism destinations. Despite this rich potential, the state's tourism department lacks a **consolidated, data-driven view** of visitor patterns across districts, seasons, and visitor types (domestic vs. foreign).

Without such visibility, decision-makers face challenges in:
- Identifying **which districts are underperforming or over-relying** on a single tourism hub (e.g., Hyderabad).
- Understanding **seasonal demand fluctuations** to plan staffing, transport, and infrastructure.
- Distinguishing between **districts with consistent, sustainable growth** versus those with erratic or declining visitor trends.
- Forecasting **future tourist inflow** to guide long-term investment and capacity planning.

**Goal of this project:** Build an interactive Power BI dashboard that consolidates historical tourist footfall data (2016–2019) across all Telangana districts, segments it by visitor type and month, and surfaces actionable insights and a 2025 visitor projection to support **data-driven tourism policy and infrastructure decisions**.

---

## 🗂️ Data Scope

📅 **4 years (2016–2019) of Domestic & Foreign visitor data**, tracked across all Telangana districts.

## 📊 Analysis & Key Insights

![Telangana Tourism Dashboard](./assets/telangana-tourism-dashboard.png)

### Dashboard Overview
The Power BI dashboard is built around four key views:
- **Filters** — by year, district, month, and visitor type (Domestic/Foreign)
- **Domestic vs. Foreign Tourist Comparison** — year-over-year visitor volume by type
- **Top 10 Districts by Domestic Tourist Footfall (2016–2019)**
- **Seasonality (Sum of Visitors by Month)**
- **District-wise Consistency Table** — flags each district as "Consistent Growth" or "Not Consistent" year over year

### Key Findings

| Metric | Value |
|---|---|
| Total Domestic Visitors (2016–2019) | **356M** |
| Projected Domestic Visitors (2025) | **4.80M** |
| Top District by Footfall | **Hyderabad** (far ahead of all other districts) |
| Peak Month | **February (58M)** |
| Lowest Month | **July (19M)** |
| Districts with Consistent Growth | Warangal (Rural), Wanaparthy, Siddipet |
| Districts with Inconsistent Trends | Hyderabad, Yadadri Bhongir, Warangal (Urban), Vikarabad, Suryapet, Sangareddy, Ranga Reddy, Rajanna Sircilla |

### Insights
1. **Hyderabad dominates footfall**, followed by Rajanna Sircilla, Warangal (Urban), and Yadadri Bhongir — indicating a heavy concentration of tourism around a few districts rather than a broad spread across the state.
2. **Seasonality is pronounced**: visitor numbers peak sharply in **February** (58M) and taper off through the year, bottoming out in **July** (19M) — likely tied to weather and holiday cycles.
3. **Only a few districts (Warangal Rural, Wanaparthy, Siddipet) show consistent year-on-year growth**, while most — including the top-performing Hyderabad — show inconsistent trends, suggesting fluctuating rather than steadily compounding demand.
4. **Tourist demand is projected to grow into 2025**, reinforcing the need for proactive infrastructure and capacity planning rather than reactive scaling.

### Recommendations
- **Diversify promotion efforts** toward high-potential but under-visited districts to reduce over-reliance on Hyderabad.
- **Plan capacity and staffing around peak season** (Dec–Feb) to avoid overcrowding, and design off-season (Jun–Aug) campaigns/discounts to smooth demand.
- **Investigate root causes of "Not Consistent" trends** in major districts (Hyderabad, Warangal Urban) — could stem from external factors (events, infrastructure disruptions) worth correcting.
- **Use the 2025 projection (4.80M)** as a baseline for infrastructure, transport, and hospitality investment planning.

---

## 🛠️ Tools Used
- **Power BI Desktop** — data modeling, DAX measures, and interactive dashboard
- Data covers **2016–2019** domestic & foreign visitor footfall across Telangana districts

## 📁 Repository Structure
```
├── README.md
├── assets/
│   ├── telangana-tourism-cover.png
│   └── telangana-tourism-dashboard.png
└── telangana_tourism.pbix   (Power BI file — add here)
```
