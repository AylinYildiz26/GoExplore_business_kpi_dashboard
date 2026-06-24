# GoExplore — Business KPI Dashboard Project

![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white)
![Looker](https://img.shields.io/badge/Looker-4285F4?style=for-the-badge&logo=looker&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)

## Overview

This repository documents an end-to-end analytics project built for **GoExplore**, a camping and hiking equipment supplier experiencing strong year-on-year growth. It was completed as a team project during the Data Science bootcamp at WBS Coding School.

GoExplore's previous data scientist left unexpectedly, leaving only a raw spreadsheet behind. The task: build a complete analytics workflow — from raw data to interactive KPI dashboards — within two weeks, and present the findings to stakeholders.

> **Note on artifacts:** This README documents the project, its approach, and its results. The underlying SQL, the Looker dashboard exports, the raw spreadsheet, and the stakeholder presentation are part of a collaborative bootcamp deliverable and are available on request.

## Approach

```
GoExplore sales data (spreadsheet, 2015–2018)
        ↓
    BigQuery
   (4 tables: daily_sales, retailers, products, methods)
        ↓
  SQL queries → Looker Studio dashboards → stakeholder presentation
```

1. Loaded the raw sales spreadsheet into **BigQuery** as four related tables (daily sales, retailers, products, order methods).
2. Wrote **SQL** queries to clean, join, and aggregate the data into business KPIs.
3. Built **Looker Studio** dashboards to visualise the KPIs and answer the stakeholders' questions.
4. Summarised the findings in a presentation for the European Division and Retailer Connections teams.

## Business Questions Answered

**1. 🌍 European Market Expansion**
> The head of the European Division wanted to expand into 4 new countries (Czech Republic, Norway, Poland, Portugal). We estimated expected market sizes by comparing these countries to similar existing GoExplore markets using revenue share, population, and GDP benchmarks.

**2. 🏪 Specialty vs. General Stores**
> The head of Retailer Connections wanted to know whether specialty stores (Golf Shops, Eyewear Stores) perform differently from general stores (Sports Stores, Outdoors Shops) — measured by Average Order Value, Average Product Price, and Orders per Store.

## Key KPIs & Insights

| KPI | Finding |
|-----|---------|
| 📈 Revenue Growth | +33% in 2016, +24% in 2017 — strong consistent growth |
| 🌍 Top Markets | USA (15.8%), UK (8.6%), Germany (8.4%) |
| 🏪 Golf Shops vs General | Golf Shops: AOV €14,640 vs Sports Stores: €5,245 |
| 📱 Order Channels | Web dominates with 124K of ~149K total orders |
| 💸 Highest Discounts | Brazil (4.36%) — high discounts, low revenue share |

## Contributors

This was a collaborative group project. Thanks to my teammates:

- Mohammad Yahya Faqirzada
- Sarah Alkhaledova
- Satish Shrestha

## 🤝 Contact

<p align="center">
  <a href="https://www.linkedin.com/in/aylinyildiz26/">
    <img src="https://user-images.githubusercontent.com/74038190/235294012-0a55e343-37ad-4b0f-924f-c8431d9d2483.gif" alt="LinkedIn" width="60">
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/AylinYildiz26">
    <img src="https://user-images.githubusercontent.com/74038190/212257468-1e9a91f1-b626-4baa-b15d-5c385dfa7ed2.gif" alt="GitHub" width="50">
  </a>
</p>
