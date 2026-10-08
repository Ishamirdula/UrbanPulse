# 🚇 UrbanPulse — Public Transport Intelligence Dashboard

**Interactive Excel dashboard for analysing public transport demand, reliability, delays, revenue, costs, and rider satisfaction.**

UrbanPulse uses **8,000 synthetic records** covering a fictional city's Metro, Bus, and Tram network from **Oct 2025 – Sep 2026**.

## 🎯 Business Questions

- Which routes and stations have the highest demand?
- When does passenger demand peak?
- Which transport type performs best?
- Which routes experience the most delays?
- Does reliability affect rider satisfaction?
- Are high-demand routes associated with higher delays?
- Which transport type has the strongest operating margin?

## 📊 Dashboard

The workbook includes:

- **Interactive filters** — Date, Transport, Route, Zone, Day Type, Peak Period & Weather
- **KPI cards** — Passengers, On-Time Rate, Average Delay, Revenue, Satisfaction & Disruption Rate
- **5 dashboard charts** — Transport Mix, Delay by Transport, Top Routes, Demand vs Delay & Monthly Trend
- **Analysis page** with operational insights
- **Prior-period KPI comparisons**
- **Automated data-quality checks**

## 🔑 Key Findings

- **M1 Red Line** is the highest-demand route — **289,987 passengers**
- **Metro** carries **61%** of total passengers
- **Grand Central** is the busiest station — **223,134 passengers**
- **Evening Peak** accounts for **41%** of passenger volume
- **Bus** has the lowest on-time rate — **86.5%**
- **B27** has the highest average delay — **4.1 min**
- **Metro** has the strongest operating margin — **19.2%**
- On-time trips have higher satisfaction — **4.13 vs 3.19**
- Route demand vs. delay correlation: **r = -0.43**

## 🛠️ Excel Techniques

Built using:

- Excel Tables & Named Ranges
- `SUMIFS`, `COUNTIFS`, `AVERAGEIFS`
- `INDEX`, `MATCH`, `LARGE`, `SUMPRODUCT`
- Data Validation & Conditional Formatting
- Native Excel charts
- Dynamic insight text
- Data-quality validation

## 📁 Workbook Structure

```text
Dashboard       → Interactive presentation layer
Analysis        → Charts & operational insights
Data            → 8,000-record TransitData table
Calculations    → KPIs, helper tables & logic
```

## 💡 Skills Demonstrated

**Data Cleaning • Excel Analytics • KPI Development • Data Visualisation • Dashboard Design • Operational Analytics • Financial Analysis • Business Storytelling**