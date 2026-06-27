# 🌍 Market Expansion Strategy for a Travel Company

## 📌 Project Overview

This project was developed as part of the Ironhack Data Analytics Bootcamp.

The objective was to build a **Market Attractiveness Framework** that helps a global online travel company identify the most attractive countries for future marketing investment using publicly available data.

Instead of relying solely on historical tourism performance, the framework combines multiple economic, digital, and tourism indicators into a single weighted score to support data-driven expansion decisions.

---

## 🎯 Business Problem

Global travel companies have limited marketing budgets and cannot invest equally across every market.

Expansion decisions are often influenced by historical performance or intuition, which may overlook emerging high-potential markets.

This project evaluates countries using objective data to identify where future marketing investment may generate the greatest opportunity.

---

## 💡 Business Hypothesis

Countries with stronger economic growth, higher digital readiness, growing online travel interest, and established tourism activity represent the most attractive markets for future expansion.

---

## 📊 Data Sources

### World Bank API
Macroeconomic and tourism indicators including:

* Tourism Arrivals
* GDP Growth
* Internet Penetration
* Population
* GDP per Capita
* Tourism Receipts
* PPP Conversion Factor

### Google Trends (PyTrends)

Used to measure current online travel interest.

### Industry Research

* OECD Tourism Reports
* UN Tourism (UNWTO)
* World Bank Publications
* Academic Research

### Competitive Landscape

Public Investor Relations materials from:

* Booking Holdings
* Airbnb
* Expedia Group

---

## 🔧 Methodology

The project followed these main steps:

1. API connection and data retrieval
2. Data cleaning and validation
3. KPI evaluation
4. Dataset integration
5. Min-Max normalization
6. Weighted scoring model
7. Exploratory Data Analysis (EDA)
8. Market attractiveness ranking
9. Industry validation

---

## 📈 Final Market Attractiveness Framework

The final scoring model used five weighted KPIs:

| KPI | Weight |
|------|--------|
| GDP Growth | 25% |
| Internet Penetration | 25% |
| Travel Interest Score | 25% |
| Tourism Arrivals | 15% |
| Population | 10% |

Each KPI was normalized using **Min-Max Scaling** before applying the business weights.

---

## 🏆 Top Recommended Markets

Based on the final framework:

1. Singapore
2. United States
3. China
4. United Arab Emirates
5. United Kingdom

---

## 📂 Repository Structure

```
├── notebooks/
│   ├── 01_API_Connection.ipynb
│   ├── 02_KPI_Selection_Data_Cleaning.ipynb
│   ├── 03_Google_Trends.ipynb
│   ├── 04_EDA_Framework.ipynb
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── presentation/
│   └── Market_Expansion_Strategy.pdf
│
├── README.md
```

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Requests
* PyTrends
* Matplotlib
* Jupyter Notebook

---

## 👥 Team

**Team BeautifulSoup**

* Andrea Zaffe
* Berker Ildokuz
* Sevgi Özdemir

Ironhack Data Analytics Bootcamp

---
## 📋 Project Management

The project was managed using an Agile workflow in Trello, including sprint planning, task assignment, progress tracking, and collaboration throughout the project.

**Trello Board:**

[https://trello.com/your-board-link](https://trello.com/invite/b/6a2d6346e965d2354623af21/ATTI1c3354c6c05e24e2cdb9214d7e283b8d006BD7B2/team-beautifulsoup-end-of-module-1-project)

---

## 📽 Presentation

Presentation Slides:

[https://docs.google.com/presentation/your-presentation-link](https://docs.google.com/presentation/d/1lNXGo8Sa0rcLqLpChMBRMuHnGhUnVPjvBDQBv7KJq0Y/edit?slide=id.p1#slide=id.p1)

---

## 📜 License

This project was created for educational purposes as part of the Ironhack Data Analytics Bootcamp.
