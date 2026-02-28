# MATH 189 — Project Proposal

**Group 7:** Anand Baidya · Dhruv Sehgal · Donghyun Koo · Daniel Huang · Kayla Li

---

## 📌 Overview

> A Comparative Analysis of Conventional and Renewable Energy

The transition from conventional energy sources (oil, coal) to renewables (wind, solar) is one of the most significant economic and environmental challenges today. This project quantitatively evaluates trade-offs across energy generation capacity, efficiency, and implementation costs to better understand the feasibility and speed of renewable energy adoption.

---

## 🗂️ Data Sources

| Source | Description |
|--------|-------------|
| **U.S. Energy Information Administration (EIA)** | Electricity generation & cost data by source (coal, petroleum, wind, solar); installed capacity, capacity factors, and fuel prices |
| **International Energy Agency (IEA)** | Cross-country datasets; electricity generation by source, investment flows, and technology cost trends |
| **International Renewable Energy Agency (IRENA)** | Renewable energy capacity, generation, and production costs; trade-offs between implementation and maintenance |
| **World Bank Open Data** | Country-level data: renewable electricity share, energy use per capita, GDP per capita |

---

## 🔬 Methodology

1. **Data Preparation** — Select, clean, and merge datasets so oil/coal and wind/solar can be compared using the same units across the same years and regions.
2. **Key Measures** — Total electricity generated, capacity factors/utilization, and implementation costs (build + operating).
3. **Exploratory Data Analysis (EDA)** — Summary tables, time trend plots, cost vs. output plots; identify patterns, outliers, and regional differences.
4. **Statistical Testing** — Based on EDA findings, apply:
   - *t-test*
   - *Mann-Whitney U test*
   - *Chi-squared test*
5. **Modeling** — If data permits, regression analysis to explore how cost and efficiency relate to renewable adoption rates over time.

---

## 📊 Expected Outcomes

A clear, data-based comparison of conventional vs. renewable energy across:
- **Electricity generation** consistency
- **Efficiency/utilization** rates
- **Implementation cost** trends and barriers

Results will highlight the biggest trade-offs and where renewables face the largest adoption challenges.

---

## 🗓️ Timeline

| Week | Tasks |
|------|-------|
| **Week 7** | Dataset selection & merging; EDA on individual and combined datasets; decide on statistical tests |
| **Week 8** | Run statistical tests; draw conclusions; produce plots and written evaluations |
| **Week 9** | Format findings into final report; refine graphs; document project timeline and reasoning |
