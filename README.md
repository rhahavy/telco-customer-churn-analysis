# GTA Housing Market Dashboard

An end-to-end data analytics project examining 26 years of Greater Toronto Area housing market data. Built to demonstrate a full analytical pipeline — from raw data to interactive dashboard — and to answer a question most housing dashboards ignore: **did the 2022 rate hikes actually help buyers?**

**[Live Dashboard →](https://your-username.github.io/gta-housing-dashboard)**

---

## The Finding

Monthly carrying costs on a GTA home rose 17% after the 2022 rate hikes — even as prices fell 16%. Buyers who waited for the "correction" paid more per month than buyers at the March 2022 price peak. This dashboard shows why, and what it means going forward.

---

## What's Inside

| Tab | Content |
|-----|---------|
| **Market Overview** | 26-year price trend, rate hike impact chart, affordability index, 4 KPI cards |
| **Supply & Demand** | SNLR, months of inventory, days on market, SP/LP ratio — the mechanics behind price movements |
| **Geographic View** | SVG choropleth across 65 GTA communities, top 5 rankings, market conditions donut |
| **Rental Market 2025** | CMHC vacancy, rents by bedroom type, condo vs purpose-built gap, turnover premium |
| **Supply & Outlook** | Feb 2026 housing starts, 1996–2032 price projection with adjustable growth rate slider |
| **Decision Tools** | Personal affordability engine, rent vs buy break-even, community comparison table |

---

## Stack

- **Data**: 136K TRREB MLS transactions (1996–2022), CMHC Rental Market Survey (Oct 2025), CMHC Housing Starts (Feb 2026)
- **Analysis**: Python · pandas · Jupyter
- **Visualization**: Chart.js · SVG (hand-coded choropleth) · vanilla JS
- **Deployment**: Single-file HTML · GitHub Pages · no frameworks · no build step

---

## Key Skills Demonstrated

`data cleaning` `exploratory analysis` `time series` `geospatial visualization` `financial modelling` `interactive dashboards` `Python` `pandas` `Chart.js` `SQL-adjacent data wrangling`
