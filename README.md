# 🏙️ NYC Airbnb Real Estate Market & Pricing Dashboard (Excel)

An end-to-end exploratory market analysis and executive dashboard built in Microsoft Excel analyzing **48,895 Airbnb listings** across New York City's 5 boroughs. 

This project evaluates daily pricing distributions, neighborhood premiums, minimum stay requirements, host review velocity, and 365-day annual availability to deliver actionable insights for prospective hosts and real estate investors.

---

## 📊 Dashboard Preview

![NYC Airbnb Dashboard](images/dashboard_overview.png)
*(Place your dashboard screenshot inside the `images/` folder)*

---

## 🎯 Business Problems & Analytical Scope

The analysis addresses 7 core commercial questions using dynamic Pivot Tables, grouped aggregations, and visual reporting:

1. **Geographic Price Premiums:** What are the most premium neighborhoods in NYC by average daily listing price?
2. **Room Type Variance:** How does pricing fluctuate across *Entire Home/Apt*, *Private Room*, and *Shared Room* across different borough groups?
3. **Stay Length Patterns:** What is the average minimum night requirement across different property types?
4. **Market Review Velocity:** How do monthly review rates vary across room types and borough markets?
5. **Top Performing Hosts:** Who are the top 10 most active hosts based on monthly review velocity?
6. **Annual Availability:** How does listing availability (out of 365 days) correlate with borough location and accommodation type?
7. **Listing Concentration:** What is the market supply distribution across the five NYC boroughs?

---

## 📈 Key Market Findings & Verified Metrics

* **Market Supply Concentration:** NYC's short-term rental market is heavily concentrated in **Manhattan (21,652 listings / 44.3%)** and **Brooklyn (20,095 listings / 41.1%)**, representing over **85%** of all active supply. Queens (5,664), the Bronx (1,090), and Staten Island (373) account for the remaining 14.6%.
* **Top Premium Neighborhoods:**
  * **Fort Wadsworth (Staten Island):** $800.00 / night (luxury waterfront/historic enclave)
  * **Woodrow (Staten Island):** $700.00 / night
  * **Tribeca (Manhattan):** $490.64 / night (highest volume premium market)
  * **Sea Gate (Brooklyn):** $487.86 / night
  * **Riverdale (Bronx):** $442.09 / night
* **Average Price by Borough & Room Type:**
  * **Manhattan:** Highest overall average at **$196.88/night** (*Entire home: $249.24*, *Private room: $116.78*, *Shared room: $88.98*).
  * **Brooklyn:** Average **$124.38/night** (*Entire home: $178.33*, *Private room: $76.50*).
  * **Citywide Benchmark:** Entire homes average **$211.79/night** vs. Private rooms at **$89.78/night** and Shared rooms at **$70.13/night**.
* **Minimum Stay Requirements:**
  * Entire apartments enforce the highest stay duration at an average of **8.51 nights**.
  * Shared rooms average **6.48 nights**, while private rooms require an average of **5.38 nights**.
* **Host Engagement & Review Velocity:**
  * Top reviewed hosts by monthly review velocity include **Row NYC (18.62 reviews/mo)** and **Nalicia (18.13 reviews/mo)**.
  * Entire homes in the **Bronx** exhibit the highest monthly review momentum (**2.24 reviews/month**), signaling strong sub-market turnover and demand.
* **Annual Occupancy & Availability:**
  * **Brooklyn** listings maintain the lowest annual availability (**100.2 days/year average**), indicating strong long-term occupancy or local restriction adherence.
  * **Staten Island** exhibits the highest annual vacancy/availability (**199.7 days/year average**).

---

## 🛠️ Excel Technical Stack & Features Used

* **Pivot Tables & Multi-Dimensional Grouping:**
  * Nested row/column dimensions comparing room types against borough hierarchies.
  * Value field settings utilizing `Average`, `Count`, and custom formatting.
* **Calculated Metrics & Advanced Formulas:**
  * Nested lookup formulas (`XLOOKUP`, `INDEX-MATCH`) and conditional aggregations (`AVERAGEIFS`, `COUNTIFS`).
  * Dynamic array and date parsing functions.
* **Dashboard Design & Data Visualization:**
  * Cohesive layout built on a dedicated sheet with gridlines removed for a clean presentation.
  * Custom bar/column charts, segmented KPI scorecards, and interactive slicers for dynamic filtering by borough and room category.
* **Data Cleansing & Validation:**
  * Preprocessing missing values in reviews per month and standardizing categorical naming across 48,000+ records.

---

## 📁 Repository Structure
