# Website Traffic Analysis

A data analysis project examining website traffic patterns, user engagement, traffic sources, and conversion behavior, built as part of the Syntecxhub Data Analyst Internship (Week 2 Project).

## 📌 Project Overview

This project analyzes ~2,000 web session records (2019–2023) to uncover insights about how users find, engage with, and convert on a website. The analysis covers traffic sources, audience demographics, engagement metrics, and page-level performance, culminating in an interactive multi-page Power BI dashboard.

## 🛠️ Tools Used

- **Python (Pandas)** — data cleaning, transformation, and exploratory analysis (Google Colab)
- **Power BI** — interactive dashboard with DAX measures
- **Dataset**: Amazon Web Traffic dataset (Kaggle)

## 📊 Dashboard Pages

### 1. Overview
KPI summary (Total Users, Avg Bounce Rate, Avg Session Duration, Total Conversions), Page Views & Conversions trend over time, and Goal Completions breakdown by Key Action type.

### 2. Traffic Sources
Breakdown of total users and conversion rates by traffic source (social media, direct, referral, organic search, paid search).

### 3. Audience Insights
User share by device category, total users by country, and conversions by day of week.

### 4. Page Performance
Page views and bounce rate distribution across key site pages (/home, /about, /products, /contact, /blog).

## 🔑 Key Insights

- **Engagement**: ~2,000 sessions analyzed (2019–2023) with an average bounce rate of ~44% and session duration of ~105 seconds.
- **Trend**: Page views and conversions fluctuate across years, with a notable dip by 2023.
- **Goal Completions**: Evenly split across action types (18–21% each) — Subscribe, Contact Form, Download, Purchase, and Sign Up — indicating balanced user intent with no single conversion type dominating.
- **Traffic Sources**: Social media drives the highest new user volume (~190–200K), with paid search lowest (~170K); conversion rates range 0–3.5% across sources, consistent with typical web benchmarks.
- **Audience**: Mobile dominates traffic at 62.7% of total users, followed by Desktop (25.8%) and Tablet (11.5%) — highlighting the need for mobile-first optimization. USA and India lead in user volume, with conversions peaking on Friday and dipping on Monday.
- **Page Performance**: The /contact page receives the highest traffic (459,904 views) but also the highest bounce rate (20.89%), suggesting a possible mismatch between visitor expectations and page content. Other pages show balanced performance with bounce rates ranging 17–21%.

## 📁 Repository Structure

```
Syntecxhub_Website_Traffic_Analysis/
├── data/
│   ├── amazon-web-traffic-dataset.csv
│   └── cleaned_traffic_data.csv
├── notebooks/
│   └── traffic_analysis.ipynb
├── dashboard/
│   ├── Website_Traffic_Analysis.pbix
│   └── screenshots/
│       ├── overview.png
│       ├── traffic_sources.png
│       ├── audience_insights.png
│       └── page_performance.png
└── README.md
```
## 📸 Dashboard Preview
![Overview](dashboard/screenshots/overview.png)
![Traffic_Sources](dashboard/screenshots/Traffic_Sources.png)
![Audience_Insights](dashboard/screenshots/Audience_Insights.png)
![Page_Performance](dashboard/screenshots/Page_Performance.png)
## 🚀 How to Use

1. Open `notebooks/traffic_analysis.ipynb` to view the data cleaning and exploratory analysis process.
2. Open `dashboard/Website_Traffic_Analysis.pbix` in Power BI Desktop to explore the interactive dashboard.

---

*This project was completed as part of the Syntecxhub Data Analyst Internship Program.*
