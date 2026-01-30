# Marketing-Campaign-Analysis
This project is an interactive power bi dashboard to analyze marketing campaign performance, high-value customers, product-wise spending and overall performance of a retail company.
## Overview

This project analyzes marketing campaign data for a retail company to understand customer behavior, campaign effectiveness, spending patterns, and channel usage. The goal is to build a consolidated analytics solution that helps stakeholders identify high-value customers, uncover under-served segments, and improve future marketing strategies.
The project integrates Python for data cleaning and EDA, SQL for analytical modeling, and Power BI for interactive dashboards.
## Business Objectives

- Identify customer segments with the highest campaign response rates (overall and per campaign).

- Analyze product-wise spending patterns across demographics.

- Evaluate channel usage (web, store, catalog, deals) among high-value customers.

- Detect under-served segments (high engagement, low spend, low response).

- Define ideal target customers for future campaigns.
## Dataset Description

[marketing_data](marketing_campaign_data.csv) – Raw data with customer-level demographics, spending, channel usage, and campaign responses.

[marketing_data_dictionary](marketing_data_dictionary.csv) – Field definitions and metadata.

[marketing_cleaned_data](marketing_data_cleaned.csv) - Cleaned data along with columns derived from existing columns in raw data.

## Tech Stack

**Python:** Pandas, NumPy (Data Cleaning, EDA, Feature Engineering)

**SQL:** Data modeling, KPIs, segment-level analytics

**Power BI:** Interactive dashboards and visualization

**Tools:** Google Colab, SQLite

## Project Workflow
### 1️⃣ Data Understanding & Cleaning (Python)

Loaded and validated datasets and data types

Handled missing values and outliers (e.g., Income, Age)

Converted date fields and derived customer tenure

**Engineered features:**

Age

Total_Spend

Total_Purchases

Children

Customer_Tenure_Days

### 2️⃣ Exploratory Data Analysis (EDA)

Univariate analysis of demographics, spending, and engagement

Bivariate analysis: response vs age, income, spend, and engagement

Product-wise spending and channel usage analysis

### 3️⃣ Rule-Based Customer Segmentation

Defined business-driven segments:

**High-Value Customers:** Top 10% by Total_Spend

**High Income Customers**

**High Web Engagement Users**

**Campaign Responders**

**Family Customers**

**Under-Served Segments** (low spend, high visits, low response)

### 4️⃣ SQL Data Modeling & Analytics

Designed customer fact table

Created analytical queries to compute KPIs:

Response Rate

Average Spend

Channel Usage Metrics

Generated segment-level summaries for dashboard consumption

### 5️⃣ Dashboard Development (Power BI)

Built interactive dashboards with filters and KPIs

Visualized campaign performance, spending patterns, and channel usage

Enabled stakeholder-driven exploration of customer segments

## 📊 Dashboard Structure
The Power BI report is organized into four logical pages, each designed to answer specific business questions and guide stakeholders from a high-level overview to actionable insights.
### Page 1: Campaign Performance Overview

- Overall and campaign-wise response rates

- Key customer KPIs

- Demographic slicers
### Page 2: Spending Patterns

Product-wise spend by demographics
### Page 3: Channel Analysis
- Which channels are most used by high-value customers

- How frequently customers interact via web channels
### Page 4: Insights Page
- Identification of under-served segments

- Behavioral differences between responders and non-responders

- Characteristics of ideal target customers for future campaigns
## Key Insights

A small percentage of customers contribute a large share of total revenue.

High-value customers spend significantly on Wine and Meat products.

Catalog and Store channels are preferred by high-value customers.

A segment with high digital engagement but low spending represents a strong conversion opportunity.
## Recommendations

Focus campaigns on high-value, high-response customer segments.

Personalize digital campaigns to convert under-served high-engagement users.

Prioritize Wine and Meat promotions for premium segments.

Optimize channel mix based on customer value and behavior.

Refine targeting using age and income bands.
