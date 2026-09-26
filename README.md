# Website Traffic & Event Analysis

## 📌 Project Overview

This project analyzes event and traffic-related data to understand **user activity, geographic patterns, popular content, and activity trends** for Alfido Tech.

## 🎯 Objectives

* Clean and prepare event data
* Analyze event activity over time
* Identify the most active countries and cities
* Identify popular artists, albums, and tracks
* Analyze event types
* Provide actionable recommendations for improving engagement

## 📂 Dataset

**Source:** Kaggle – Website Traffic Analysis

[Dataset Link](https://www.kaggle.com/datasets/bhanupratapbiswas/website-traffic-analysis)

### Dataset Columns

`event, date, country, city, artist, album, track, isrc, linkid`

## 🛠️ Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

## 🔍 Data Preparation

* Checked missing values
* Removed duplicate records
* Converted the `date` column
* Created Year, Month, and Day features

## 📊 Analysis Performed

### Event Analysis

* Event type distribution
* Daily event trends
* Monthly event trends

### Geographic Analysis

* Top countries
* Top cities
* Event distribution by country

### Content Analysis

* Top artists
* Top albums
* Top tracks
* Artist-level performance

## 📈 Visualizations

### Monthly Events

![Monthly Events](charts/monthly_events.png)

### Top Countries

![Top Countries](charts/top_countries.png)

### Top Cities

![Top Cities](charts/top_cities.png)

### Top Artists

![Top Artists](charts/top_artists.png)

### Top Tracks

![Top Tracks](charts/top_tracks.png)

### Event Types

![Event Types](charts/event_types.png)

## 💡 Recommendations

1. Focus campaigns on high-activity locations.
2. Promote popular artists and tracks.
3. Optimize experiences around frequently occurring event types.
4. Improve content discovery using popular content.
5. Monitor activity trends to plan campaigns and engagement strategies.

## ⚠️ Data Limitation

The dataset does not contain dedicated fields for **sessions, session duration, bounce rate, users, or conversion rate**. Therefore, these metrics are not calculated in this project.

## 📁 Project Files

* 📓 [Jupyter Notebook](Website_Traffic_Analysis.ipynb)
* 📄 [Short Report](Website_Traffic_Analysis_Report.pdf)
* 📊 [Charts](charts/)

## 📋 Deliverables

* Jupyter/Colab notebook with analysis and visualizations
* Short report containing key insights and recommendations
