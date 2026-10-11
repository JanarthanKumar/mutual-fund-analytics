# 📈 Mutual Fund Analytics Platform
> **Full-Stack Data Engineering & Financial Intelligence Platform**  
> *Bluestock Fintech Capstone Project*

An end-to-end mutual fund analytics platform analyzing **₹12.5L Cr AUM** across **10 Asset Management Companies (AMCs)**, **40 schemes**, and **46,000+ daily NAV records**. The platform features an automated Python ETL pipeline, a relational star schema database, quantitative risk-adjusted performance modeling, and an interactive 4-page Power BI executive suite.

---

## 🎯 Capstone Objectives & Deliverables

| Deliverable | Description | Key Tech / Artifacts |
| :--- | :--- | :--- |
| **O1 · Automated ETL Pipeline** | Ingestion, data cleaning, and currency normalization of historical NAV and AMFI feeds | `etl_pipeline.py`, Pandas, NumPy |
| **O2 · Relational Star Schema** | Production-ready star schema separating dimensional attributes from transactional fact metrics | SQLite / PostgreSQL, `schema.sql` |
| **O3 · Exploratory Data Analysis** | Trend decomposition of mutual fund AUM and systemic SIP inflows | `eda_analysis.ipynb`, Matplotlib, Seaborn |
| **O4 · Risk & Performance Analytics** | Quantitative calculation of Sharpe, Sortino, Maximum Drawdown, and 95% Historical VaR | `metrics_analysis.ipynb`, `fund_sharpe_ranks.csv` |
| **O5 · Interactive Executive Dashboard** | 4-page Power BI dashboard detailing market movements, risk matrices, and investor behavior | `Mutual_Fund_Analytics.pbix`, 4-Page PDF Export |

---

## 📊 Key Insights & Analytical Findings

* **Systematic Inflow Growth:** Monthly SIP contributions exhibited continuous growth across economic cycles, hitting a milestone peak of **₹31,002 Cr** by December 2025.
* **Demographic Shift:** **31% of total investors are under 30 years old**, representing the fastest-adopting cohort for recurring automated investment plans.
* **Tier-2 Expansion:** Investor inflows in Tier-2 regions expanded by **+19% YoY**, outpacing Tier-1 metropolitan inflows by 2.5x.
* **Geographic Distribution:** Retail mutual fund participation remains anchored in the top 5 states: **Maharashtra, Karnataka, Tamil Nadu, Delhi, and Gujarat**.
* **Risk-Adjusted Alpha:** Top-decile equity schemes sustained Sharpe ratios $> 1.45$ while holding maximum drawdown within acceptable parameters compared to the Nifty 50 TR benchmark.

---

## 🖥️ Interactive Dashboard Architecture (Power BI)

The executive dashboard is organized into 4 distinct views:
1. **Market Overview:** AMC-level AUM leaderboards, monthly SIP trajectory curve, and macro KPI cards.
2. **Fund Performance & Risk Analysis:** Sharpe vs. Sortino risk-return scatter matrix with dynamic category/AMC cross-filtering and tabular risk scorecards.
3. **Investor Demographics:** Geographic distribution across top states, city-tier transaction velocity, and SIP vs. Lumpsum volume splits.
4. **Portfolio Holdings & Sector Exposure:** Interactive scheme-level equity breakdown displaying sector exposure treemaps and top 10 concentrated stock positions.

---

## 🛠️ Technology Stack

* **Data Engineering:** Python (`pandas`, `numpy`, `sqlalchemy`, `requests`)
* **Database & Modeling:** Relational Star Schema (Fact & Dimension modeling)
* **Statistical & Risk Analysis:** SciPy, Sharpe & Sortino ratios, 95% Historical Value-at-Risk (VaR)
* **Business Intelligence & Visualization:** Microsoft Power BI Desktop, Matplotlib, Seaborn
