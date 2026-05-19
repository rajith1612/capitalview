# 📊 CapitalView — FP&A Financial Analytics & Executive KPI Dashboard

> Built by **Lakshman Rajith Rongala** | University of New Haven | [LinkedIn](https://www.linkedin.com/in/lakshmanrajith) | [Portfolio](https://www.artfolio.tech/lakshmanrongala) | [GitHub](https://github.com/rajith1612)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)

---

## 🚀 Overview

**CapitalView** is an end-to-end FP&A financial analytics platform that ingests financial data into **Snowflake** via Python ETL pipelines, performs **variance analysis, rolling forecasts, and budget vs actuals comparisons**, and delivers **executive-ready Power BI and Tableau dashboards** for leadership decision-making.

Built to replace manual Excel-based reporting workflows — reducing reporting time from **3+ hours to under 30 minutes** and improving **forecast accuracy by 22%**.

---

## ✨ Features

- 📈 **FP&A Executive Dashboard** — Budget vs Actuals, variance analysis, rolling forecasts
- 🛒 **Amazon Marketplace Analytics** — Revenue by category, take rate trends, seller performance
- 💰 **Profitability & COGS Analysis** — Margin analysis, cost breakdown, profitability KPIs
- 📊 **Executive Financial Performance** — C-suite ready financial reporting and KPI tracking
- 🔄 **Automated ETL Pipelines** — Python + SQL data cleaning and transformation
- 📉 **DCF Valuation Models** — Excel-based financial modeling and forecasting

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python, SQL |
| Analytics | Pandas, NumPy |
| Visualization | Power BI, Tableau, Matplotlib |
| Database | Snowflake, PostgreSQL |
| Reporting | Excel (VBA, Pivot Tables), DAX |
| Financial Modeling | DCF, Budget vs Actual, Forecasting |

---

## 📁 Project Structure

```
capitalview/
├── 01_FPA_Executive_Dashboard/
│   ├── python/               # Data cleaning & analysis
│   ├── sql/                  # Schema & KPI queries
│   ├── dashboards/           # Power BI (.pbix) files
│   ├── excel/                # Forecast & DCF models
│   └── outputs/              # Charts & visualizations
├── 02_Amazon_Marketplace_Analytics/
│   ├── python/
│   ├── sql/
│   ├── dashboards/
│   └── excel/
├── 03_Profitability_and_COGS_Analysis/
│   ├── python/
│   ├── sql/
│   └── dashboards/           # Tableau (.twbx) files
├── 04_Executive_Financial_Performance/
│   ├── python/
│   ├── sql/
│   └── dashboards/
├── Images/                   # Dashboard screenshots
└── README.md
```

---

## 📊 Dashboard Previews

### FP&A Executive Dashboard
![FPA Dashboard](Images/FPnA_Executive_Analytics_Dashboard.png)

### Executive Financial Performance
![Executive Dashboard](Images/Executive%20Financial%20Performance%20Dashboard..png)

### Amazon Marketplace Analytics
![Amazon Dashboard](Images/amazon_dashboard_thumbnail.png)

---

## ⚙️ Setup & Usage

```bash
# Clone the repo
git clone https://github.com/rajith1612/capitalview.git
cd capitalview

# Install dependencies
pip install pandas numpy matplotlib sqlalchemy snowflake-connector-python

# Run data cleaning pipeline
python 01_FPA_Executive_Dashboard/python/01_data_cleaning.py

# Run analysis & chart generation
python 01_FPA_Executive_Dashboard/python/02_analysis_charts.py

# Open Power BI dashboards
# Open .pbix files in Power BI Desktop

# Open Tableau dashboards
# Open .twbx files in Tableau Desktop
```

---

## 📈 Key Results

| Metric | Result |
|--------|--------|
| Reporting Time Reduction | 3+ hours → 30 minutes |
| Forecast Accuracy Improvement | +22% |
| KPIs Tracked | 15+ financial KPIs |
| Data Sources Integrated | 4 business units |
| Dashboard Coverage | FP&A, Marketplace, COGS, Executive |

---

## 📬 Contact

**Lakshman Rajith Rongala**
- 📧 Email: lakshmanrajith777@gmail.com
- 💼 LinkedIn: [linkedin.com/in/lakshmanrajith](https://www.linkedin.com/in/lakshmanrajith)
- 🌐 Portfolio: [artfolio.tech/lakshmanrongala](https://www.artfolio.tech/lakshmanrongala)
- 🐙 GitHub: [github.com/rajith1612](https://github.com/rajith1612)
