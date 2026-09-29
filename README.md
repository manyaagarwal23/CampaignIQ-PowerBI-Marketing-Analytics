# CampaignIQ – Marketing Campaign Analytics Dashboard

CampaignIQ is an interactive Power BI dashboard developed to analyze marketing campaign performance and understand the effectiveness of different marketing channels, products, and categories.

## Project Overview

The project uses marketing campaign data containing information such as advertising spend, impressions, clicks, conversions, revenue, campaign dates, products, categories, and marketing channels.

The data was analyzed and visualized using Microsoft Power BI to create an interactive three-page dashboard.

## Dashboard Pages

### 1. Executive Overview

Provides a high-level summary of overall marketing performance.

Key metrics include:

- Ad Spend
- Revenue
- ROAS
- CTR
- Conversion Rate
- CPA

The page also includes visualizations for marketing trends, spending, revenue, channels, impressions, and clicks.

### 2. Campaign Intelligence

Provides detailed campaign and marketing-channel analysis.

It includes:

- Campaign performance table
- Campaign-level spend and revenue
- ROAS analysis
- CTR and conversion rate
- CPA
- ROAS by marketing channel
- Conversion rate by marketing channel
- Spend vs ROAS analysis
- Interactive filters for category, product, marketing channel, and date

### 3. Budget Scenario Simulator

An interactive scenario analysis page that allows users to change the marketing budget and observe the resulting scenario values.

The page includes:

- Current Spend
- Scenario Spend
- Current Revenue
- Scenario Revenue
- Scenario ROAS
- Revenue Impact
- Spend Impact

The scenario model assumes that revenue changes proportionally with the selected budget adjustment. It is intended for exploratory analysis rather than forecasting.

## Key KPIs

| KPI | Description |
|---|---|
| Ad Spend | Amount spent on marketing campaigns |
| Revenue | Revenue generated from campaigns |
| ROAS | Revenue generated relative to advertising spend |
| CTR | Click-through rate |
| Conversion Rate | Percentage of clicks resulting in conversions |
| CPA | Cost per conversion |

## Tools Used

- Microsoft Power BI
- DAX
- Microsoft Excel
- Data Visualization
- Business Intelligence

## Dataset

The dataset contains marketing campaign information including:

- Campaign ID
- Product Name
- Category
- Ad Spend
- Impressions
- Clicks
- Conversion
- Revenue
- Campaign Date
- Marketing Channel
- ROAS
- ROI

## Key Features

- Interactive Power BI dashboards
- KPI-based marketing analysis
- Campaign-level analysis
- Marketing-channel comparison
- Interactive slicers and filters
- DAX-based calculations
- Budget What-If analysis
- Scenario-based spend and revenue analysis

## Project Structure

```text
CampaignIQ/
│
├── CampaignIQ_Marketing_Analytics.pbix
├── Marketing_Campaign_Dataset.xlsx
├── README.md