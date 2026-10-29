<p align="center">
  <img src="assets/banner.svg" alt="Harsha Manjunath, Data and BI analyst, Christchurch NZ" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/based%20in-Christchurch%2C%20NZ-38bdf8?style=flat-square" alt="Christchurch NZ">
</p>

## Hey, I'm Harsha 👋

I turn messy data into numbers a business can actually trust. Right now I'm a BI and Data Analyst Trainee in Christchurch, and before that I did a Master of Artificial Intelligence at the University of Canterbury.

I also spent a good while working in warehouses and distribution centres, so I've seen firsthand what happens when the forecast is wrong and the shift is short-staffed. That's a big part of why I care about honest baselines and plain-English results.

Nearly every project below runs on a **real public dataset**, ships with the data so it runs straight after cloning, and is checked by a GitHub Action on every push. (The retail toolkit is the one exception and uses synthetic data on purpose.)

## 📊 The results wall

One real number from each project, straight from the included run.

| | Project | The question | What came out |
|:-:|:--|:--|:--|
| 🏏 | [**cricket-win-probability**](https://github.com/harsha089999/cricket-win-probability) | Who's winning this IPL chase, ball by ball? | **0.96 AUC** in the death overs, tested on seasons the model never saw |
| 🧊 | [**cold-chain-anomaly-detection**](https://github.com/harsha089999/cold-chain-anomaly-detection) | Can we catch a failing machine early? | **4 of 4** labelled failures caught, first one flagged 1.3 hours in |
| ⚡ | [**nz-electricity-demand-forecast**](https://github.com/harsha089999/nz-electricity-demand-forecast) | How much power will the grid need tomorrow? | **6.0% MAPE** against 7.3% for "same hour yesterday" |
| 🛒 | [**nz-retail-sales-forecasting**](https://github.com/harsha089999/nz-retail-sales-forecasting) | What will each retail industry turn over next year? | **1.4% MAPE** for supermarkets, and a naive baseline beat the fancy models for hardware |
| 📞 | [**explainable-churn-prediction**](https://github.com/harsha089999/explainable-churn-prediction) | Who's about to leave, and why? | Top 100 call list is **3x better** than random, with each customer's top 3 reasons |
| 🧹 | [**kpi-data-quality-pipeline**](https://github.com/harsha089999/kpi-data-quality-pipeline) | Can we trust today's KPIs? | 11 SQL checks, **255 bad orders** quarantined before anything hits a dashboard |
| 💬 | [**review-sentiment-analytics**](https://github.com/harsha089999/review-sentiment-analytics) | What are customers actually unhappy about? | **0.98 ROC-AUC** on 22k real reviews, rolled up into Power BI tables |
| 🤖 | [**text-to-sql-bi-assistant**](https://github.com/harsha089999/text-to-sql-bi-assistant) | Can anyone ask the warehouse a question safely? | Plain English to SQL, with a guard that **blocked every destructive query** |
| 📦 | [**warehouse-labour-planning**](https://github.com/harsha089999/warehouse-labour-planning) | How many pickers does each zone need next week? | Zone-level forecasts turned into a **7-day staffing plan** |
| 🎯 | [**promotion-uplift-analysis**](https://github.com/harsha089999/promotion-uplift-analysis) | Which promo actually sells more? | A 3-arm test across 137 stores, adjusted for market size and backed by a bootstrap |
| 🏪 | [**retail-commercial-analytics**](https://github.com/harsha089999/retail-commercial-analytics) | Sales and margin toolkit for a retail team | dbt + DuckDB pipeline with an Excel front end and tests |

## ✍️ Something different

**[Quire Writer](https://harsha089999.github.io/quire-writer/)** is a full word processor in a single HTML file. Ribbon toolbar, page layout, tables, find and replace, and it opens and saves real Word files. Nothing leaves your browser. [Try it here.](https://harsha089999.github.io/quire-writer/)

## 🧰 What I work with

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black" alt="DuckDB">
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" alt="dbt">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
</p>

## 🧭 How I like to work

- **Beat the baseline or say so.** Every forecast gets compared against "same as last week". Sometimes last week wins, and that's worth knowing.
- **Quarantine, don't delete.** Bad rows get set aside with a reason, never quietly dropped.
- **Answer the business question first.** Each README opens with the question someone would actually ask.

<br>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/harsha089999/harsha089999/output/snake-dark.svg">
    <img src="https://raw.githubusercontent.com/harsha089999/harsha089999/output/snake.svg" alt="Contribution snake eating my commit graph">
  </picture>
</p>

<p align="center"><sub>Always happy to chat about forecasting, cricket stats, or why the naive model keeps winning.</sub></p>
