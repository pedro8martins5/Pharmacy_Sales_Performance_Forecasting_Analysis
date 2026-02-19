![image_atl](https://github.com/pedro8martins5/Pharmacy_Sales_Performance_Forecasting_Analysis/blob/main/GreenCross%20Pharmacy.png?raw=true)


<div align="center">
  <h1>Pharmacy Sales Performance & Forecasting Analysis</h1>
</div>

GreenCross Pharmacy is a fictional multi-national pharmacy group operating across **Portugal, Spain, and Germany**, created to simulate a realistic European pharmaceutical retail environment.

Over a five-year period (2014-2019), the business generated **€127.6K in total revenue**, averaging **€25.5K per year**. Across the analysed timeframe, performance delivered an overall **+20.09% positive variation**, signalling structural growth despite annual volatility.

Revenue peaked in **2016 (€25.23K)** before declining to its lowest point in **2019 (€17.09K)** - a contraction that exposes operational sensitivity and the importance of demand-aligned inventory strategy.

Seasonality is not incidental - it is structural.
**January consistently emerges as the strongest month (€14K average)**, while **July represents the weakest (€8.8K average)**. Unlike traditional retail environments where Q4 dominates, GreenCross frequently sees **Q1 outperforming Q4**, indicating that demand is driven by health cycles rather than consumer spending seasons.

Portfolio concentration is equally revealing.
**Paracetamol alone accounts for 58% of total revenue**, creating both stability and risk. While its OTC nature, affordability, and broad treatment use justify its dominance, this level of dependency introduces exposure to pricing pressure, supply disruption, and margin compression.

Other therapeutic categories remain relatively balanced, contributing between **5–10% each**, with **Hypnotics & Sedatives representing just 1.15%**, reinforcing limited diversification depth.

Sales patterns remain consistent across all five years, confirming that these dynamics are not anomalies but structural behaviours embedded in the business model.

## Key Focus Areas

* **Revenue Sustainability & Growth Quality - Understanding whether revenue performance reflects structural growth or short-term fluctuations, and identifying the underlying drivers of financial stability across markets.**
* **Seasonality & Demand Behaviour - Analysing recurring consumption patterns to determine how demand shifts throughout the year and how operational planning should adapt accordingly.**
* **Product Portfolio Balance & Risk Exposure - Evaluating the concentration of sales across therapeutic categories to assess dependency risks, resilience, and long-term portfolio sustainability.**
* **Operational Efficiency & Sales Distribution - Assessing how sales distribute across time periods to support more efficient staffing, opening-hour optimization, and stock replenishment cycles.**
* **Inventory Optimization & Predictive Planning - Aligning historical demand behaviour with forward-looking forecasting models to ensure optimal stock levels, minimise waste, and protect revenue continuity.**

<div align="center">
  <h1>Executive Summary</h1>
</div>

![image_atl](https://github.com/pedro8martins5/Pharmacy_Sales_Performance_Forecasting_Analysis/blob/main/Sales%20Revenue%20Analysis.png?raw=true)

| **1.Revenue Trend Evolution** | **2.Peak Performance Periods** |
|------------------------------|-------------------------------|
| Revenue shows cyclical behaviour across the five-year period, fluctuating around an average monthly baseline of approximately **1.82K**, clearly marked by the horizontal reference line. | The most pronounced revenue peak occurs in early 2019, reaching approximately **2.8K**, representing the highest single-month performance in the entire period. |
| From 2014 through 2016, performance progressively strengthens, with higher highs forming year over year, suggesting momentum building into 2016–2017. | Additional strong peaks are visible in 2016 and 2017, exceeding **2.5K–2.7K**, indicating repeated periods of accelerated demand rather than isolated outliers. |
| Post-2017, volatility increases, with sharper swings between highs and lows, signalling a less stable revenue pattern compared to earlier years. | These peak clusters are concentrated in specific periods rather than evenly distributed, highlighting identifiable high-demand windows. |

---

| **3.Revenue Declines & Volatility** | **4.Structural Patterns & Stability** |
|-----------------------------------|--------------------------------------|
| Several significant troughs fall near the **1.3K–1.4K** range, particularly during 2017 and 2018, reflecting recurring low-performance intervals. | Despite fluctuations, most monthly results remain within a controlled performance band between **1.4K and 2.3K**, reinforcing structural stability. |
| The most extreme drop appears at the end of 2019, falling sharply to approximately **0.5K**, clearly deviating from historical patterns and signalling an anomaly. | The repeated oscillation around the average baseline suggests seasonality-driven behaviour rather than erratic market disruption. |

<div align="center">
  <h1>Dataset Structure and Data Model</h1>
</div>

Centralized sales data model integrating time dimensions and pharmaceutical sales across hourly, daily, weekly, and monthly tables, encompassing **43 columns and 771,814 rows.**
![image_atl](https://github.com/pedro8martins5/Pharmacy_Sales_Performance_Forecasting_Analysis/blob/main/GreenCross%20Data%20Model.png?raw=true)
