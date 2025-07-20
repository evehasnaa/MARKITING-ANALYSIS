# Campaign Performance Analysis Dashboard

This repository contains a full Power BI project analyzing the performance of digital marketing campaigns across multiple platforms.

## 🔍 Overview

The dashboard helps stakeholders and marketers monitor:

* Cost efficiency (CPC, CPA)
* Conversion performance (CTR, Conversion Rate)
* Audience insights by age, gender, and region
* Campaign performance trends over time

## 📊 Dashboard Pages

### 1. Performance Overview

* KPIs: Total Impressions, Clicks, Cost, Conversions, CTR, Conversion Rate
* Visuals: Campaign conversions, budget by platform, filters by platform, objective, and date

### 2. Cost & Efficiency

* KPIs: CPC, CPA, Total Cost
* Visuals: CPA/CPC by campaign, cost trend by time, filters for deeper analysis

### 3. Audience Insights

* KPIs: Average Engagement Rate, Reach, Campaign Count
* Visuals: Engagement by age group and gender, region-based reach

### 4. Campaign Effectiveness

* Visuals: Campaign duration vs conversions, objective performance, conversion efficiency by platform
* Insights & Recommendations

## 🧮 Key DAX Measures

```DAX
CTR = DIVIDE(SUM('Ads'[Clicks]), SUM('Ads'[Impressions]))
CPC = DIVIDE(SUM('Ads'[Cost]), SUM('Ads'[Clicks]))
CPA = DIVIDE(SUM('Ads'[Cost]), SUM('Ads'[Conversions]))
Conversion Rate = DIVIDE(SUM('Ads'[Conversions]), SUM('Ads'[Clicks]))
Engagement Rate = DIVIDE(SUM('Ads'[Likes]) + SUM('Ads'[Shares]) + SUM('Ads'[Comments]), SUM('Ads'[Reach]))
```

## 📌 Key Insights

* Facebook campaigns yielded the highest conversion rate.
* Female audience aged 25–34 showed the best engagement.
* TikTok ads delivered the lowest CPA with short video creatives.

## 💡 Recommendations

* Reinvest in high-performing video content on Facebook.
* Target younger male audiences in underperforming regions.
* Optimize campaign duration and test creatives by objective.

## 🧠 Tools Used

* Microsoft Power BI
* Power Query
* DAX

## 🌐 View the Dashboard Online

You can view the interactive dashboard [[PS C:\markiting challange (data analysise)> git push -u origin main
fatal: unable to access 'https://github.com/evehasnaa/MARKITING-ANALYSIS.git/': Could not resolve host: github.com ](https://app.powerbi.com/groups/3d3a4bf0-61d0-42a8-a6e4-018d07a90999/reports/c50537a0-dd81-4276-8079-d9901ce5dd54/99e6ca003e3c9bcb1bc9?experience=power-bi)](#)  <!-- Replace # with Power BI public link -->

## 🧑‍💻 Author

**Hasnaa Ahmed**
Data Analyst | Power BI Developer
