### Social Media Advertisement Performance Analysis

This project analyzes the performance of social media advertisements across platforms such as Facebook and Instagram. It uses event level data that includes impressions, clicks, likes, comments, shares and purchases. The goal is to understand user engagement, platform trends, campaign effectiveness and future performance using statistical modeling.

Overview

The project contains

A Power BI report that visualizes ad performance

Predictive modeling using ARIMA for forecasting event counts

Data tables from multiple sources such as ad events, ads metadata, campaigns and user demographics

A Keynote presentation summarizing insights

Supporting documentation and assets included in this repository

Data Sources

The project uses four primary data tables.

1. Ad Events

Contains event level interactions for every ad.
Columns include
event_id, ad_id, user_id, timestamp, day_of_week, time_of_day, event_type

2. Ads

Contains ad metadata such as
ad_id, campaign_id, ad_platform, ad_type, target_gender, target_age_group, target_interests

3. Campaigns

Contains campaign level information such as
campaign_id, name, start_date, end_date, duration_days, total_budget

4. Users

Contains user demographics such as
user_id, user_gender, user_age, age_group, country, location

Visualizations

The Power BI report provides insights for

Event patterns by day, time and platform

Engagement metrics

Demographic patterns

CTR and conversion metrics

Campaign performance

Predicted event activity using ARIMA

Modeling

An ARIMA model is used to forecast event counts over time. Additional models that can be added include

SARIMA

Prophet

LSTM

Exponential smoothing models

How to Use

Open the Power BI file and connect to your dataset if needed

Explore the dashboard pages including overview, ad platform, demographics and event behavior

Review the forecasting scripts in Python if included

Refer to the Keynote for summary insights

Requirements

Power BI Desktop

Python with pandas and statsmodels

Data files in CSV or database format

macOS for viewing Keynote presentation (or iCloud online viewer)

Future Improvements

Add automated data refresh

Deploy forecast results to Power BI

Include more machine learning models

Add anomaly detection for unusual ad performance spikes
