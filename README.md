# Power-BI--Malaysian-immigration-analysis
🛂 Malaysian Immigration Analysis - Excel + Power BI

## 📌 Project Overview
A comprehensive data analysis project examining **Malaysian immigration patterns** using Excel for data cleaning and Power BI for interactive visualization. This project uncovers key trends in visitor arrivals trend, top countries of origin, state of entries, and demographic insights.

## Dataset used
- <a href="https://github.com/Donovandonz/Power-BI--Malaysian-immigration-analysis/blob/main/arrivals_soe.csv">RAW.MalaysianIMMI</a>


## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **📗 Excel** | Data cleaning, transformation, and initial exploration |
| **📊 Power BI** | Interactive dashboard creation, DAX calculations, and visualization |

---

## 📂 Data Workflow

### 🔧 Step 1: Excel Data Cleaning
- ✅ Removed duplicates, Delete unwanted column and handled missing values in immigration records
- ✅ Standardized country names and port of entry formats
- ✅ Converted date formats for consistency
- ✅ Created calculated columns for visitor categories
- ✅ Built pivot tables for initial trend analysis
- ✅ Exported clean dataset for Power BI

- ### 📊 Step 2: Power BI Dashboard
- ✅ Imported cleaned Excel data
- ✅ Created data model and relationships
- ✅ Developed DAX measures for key metrics
- ✅ Designed interactive visuals, KPI Cards and slicers
- ✅ Published interactive dashboard

---

## 📑 Dashboard Layout

| Chart | Description |
|------|-------------|
| **📈 Foreigner arrival trend** | Time-series analysis: Track monthly and yearly growth in international visitor volume |
| **🌍 Total foreigner from their origin/country** | Source Markets: Total foreigner count categorized by their specific country of origin |
| **🚪 State of entry** | Geographic distribution: Breakdown of arrivals by Malaysian states and primary entry points |
| **📋 Type of gender by state of entries** | Gender & Profile: Analysis of male vs. female arrivals categorized by their specific state of entry |

---

# 📈Foreigner Arrival Trends (2020-2024)

This repository tracks the recovery of international arrivals following the global pandemic, highlighting the transition from a total shutdown to a stabilized growth phase.

## 📊 Dataset Overview

| Year | Arrival Volume | YoY Change (%) | Phase |
| :--- | :--- | :--- | :--- |
| **2020** | 6,172,008 | — | Pandemic Impact |
| **2021** | 470,559 | -92.4% 📉 | Market Bottom |
| **2022** | 15,148,512 | +3,119% 🚀 | Revenge Travel |
| **2023** | 30,515,304 | +101.4% 🏗️ | Full Recovery |
| **2024** | 31,899,166 | +4.5% ✅ | Stabilization |

## 📈 Recovery Visualization



## 💡 Key Insights

### 1. The 2021 Trough
The **92.4% collapse** in 2021 represents the absolute nadir of global mobility. This was driven by the "Delta variant" waves and the lag between vaccine rollouts and border re-openings.

### 2. The Statistical Anomaly of 2022
The **3,119% growth** in 2022 is a rare statistical outlier. It marks the "Revenge Travel" phenomenon where two years of suppressed demand were released simultaneously as entry requirements (PCR tests/quarantine) were abolished.

### 3. Shift to Sustainable Growth
By 2024, the growth rate slowed to **4.5%**. This is a healthy sign. It suggests the market has moved past the volatile "recovery" phase and has entered a standard growth cycle based on organic economic factors rather than policy changes.

---

## 🌍 Top 5 Source Markets (Origin Country)

The following countries represent the primary drivers of international arrivals. Singapore remains the undisputed leader, contributing more than the other four top markets combined.

| Rank | Country of Origin | Total Arrivals | Market Share (%) | Status |
| :--- | :--- | :--- | :--- | :--- |
| 1 | **Singapore** 🇸🇬 | 41,120,085 | 62.2% | Primary Hub |
| 2 | **Indonesia** 🇮🇩 | 9,886,077 | 14.9% | Key Regional Partner |
| 3 | **Thailand** 🇹🇭 | 6,395,376 | 9.7% | High Growth |
| 4 | **China** 🇨🇳 | 5,577,427 | 8.4% | Strategic Market |
| 5 | **Brunei** 🇧🇳 | 3,139,296 | 4.8% | Cross-Border Traffic |

### 🔍 Market Insights

* **Singapore Dominance:** With over 41 million arrivals, Singapore accounts for roughly **62%** of the top-tier traffic. This suggests a high volume of short-term cross-border commuters or business travelers.
* **ASEAN Strength:** Four out of the top five countries (Singapore, Indonesia, Thailand, and Brunei) are ASEAN members. This highlights the critical importance of regional intra-travel and land-border connectivity.
* **China’s Positioning:** Despite being 4th, China remains the only non-neighboring country in the top 5, indicating its massive influence as a long-haul/medium-haul tourism powerhouse for the region.

---

## 🚪 State of Entry: Geographic & Gender Distribution

This section breaks down the primary entry points into Malaysia, categorized by State and Gender. Johor remains the dominant gateway, largely due to land-border connectivity with Singapore.

### 📍 Top 3 Entry States by Volume

| Rank | State | Male Arrivals | Female Arrivals | Total Arrivals | Gender Ratio (M:F) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | **Johor** 🌉 | 26,608,741 | 21,121,614 | **47,730,355** | 1.26:1 |
| 2 | **Selangor** ✈️ | 11,888,010 | 8,969,436 | **20,857,446** | 1.32:1 |
| 3 | **Sarawak** 🌳 | 2,502,605 | 2,090,693 | **4,593,298** | 1.20:1 |


### 🔍 Geographic Insights

* **Johor (The Southern Gateway):** Accounting for nearly **48 million** arrivals, Johor’s massive lead is driven by the Causeway and Second Link. The relatively balanced gender ratio suggests a high volume of family travel and daily commuting.
* **Selangor (The Aviation Hub):** As the home of KLIA and KLIA2, Selangor represents the primary "Air Entry" point. The higher male-to-female ratio (**1.32:1**) often correlates with international business travel trends typical of major aviation hubs.
* **Sarawak (The East Malaysian Corridor):** While 3rd in volume, Sarawak shows the most balanced gender distribution (**1.20:1**), reflecting strong cross-border social and trade ties with Brunei and Kalimantan, Indonesia.

---

## 📋 Gender Profile: Global State Distribution

This section provides a high-level overview of the gender demographics for all international arrivals across all Malaysian states.

### 👥 Aggregate Gender Breakdown

| Gender | Total Arrivals | Percentage (%) | Trend Indicator |
| :--- | :--- | :--- | :--- |
| **Male** 👨 | 46,940,985 | 55.7% | 📈 High |
| **Female** 👩 | 37,264,564 | 44.3% | 📉 Moderate |
| **Total** | **84,205,549** | **100%** | **Combined Volume** |


**Traveler Profiling:**
   The consistent **11.4% gap** between male and female arrivals across all states likely reflects a combination of:
   * **Business & Labor Migration:** Historically higher male volumes in the construction and manufacturing sectors.
   * **Regional Commuting:** Daily cross-border workers in the Singapore-Johor corridor.

---

# Dashboard Overview
- <a href="https://github.com/Donovandonz/Power-BI--Malaysian-immigration-analysis/blob/main/Malaysian-Immigration-Dashboard.png">Malaysian-IMMI-Dashboard

  <img width="1310" height="737" alt="Malaysian-Immigration-Dashboard" src="https://github.com/user-attachments/assets/ae12d212-e4e6-49eb-9009-b757ac7fffac" />
