# music-analytics-pipeline
Music analytics pipeline using Last.fm API featuring data extraction, EDA, custom metrics and historical trend analysis.
#  Music Analytics Pipeline using Last.fm API

## Project Overview

This project is an end-to-end music analytics pipeline built using the Last.fm API and Python. It collects real-time music data, performs exploratory data analysis, engineers custom performance metrics, and maintains historical datasets for trend analysis.

The project demonstrates API integration, data cleaning, feature engineering, historical data management, and data visualization using Python.

---

## Objectives

- Extract artist and track data from the Last.fm API
- Build structured datasets using Pandas
- Perform exploratory data analysis
- Engineer custom music analytics metrics
- Maintain cumulative historical datasets
- Visualize artist and track performance
- Create a foundation for future dashboards and automation

---

## Technologies Used

- Python
- Pandas
- Requests
- Matplotlib
- Jupyter Notebook
- Last.fm API

---

## Project Workflow

Last.fm API

↓

JSON Data Extraction

↓

Data Cleaning

↓

Pandas DataFrames

↓

CSV Storage

↓

Historical Data Pipeline

↓

Feature Engineering

↓

Exploratory Data Analysis

↓

Visualizations

---

## Features

### Data Extraction

- Top Artists
- Top Tracks
- API integration using Requests
- JSON parsing

### Data Storage

The project automatically stores:

- top_artists.csv
- top_tracks.csv
- artists_history.csv
- tracks_history.csv

Historical datasets are appended with the current extraction date to enable trend analysis over time.

---

## Feature Engineering

The project includes several custom analytics metrics including:

- Artist Performance Index
- Popularity Score
- Underrated Score
- Listeners per Play
- Track Duration (Minutes)

---

## Exploratory Data Analysis

The notebook performs analyses including:

- Top artists by listeners
- Top artists by playcount
- Top tracks
- Artist frequency analysis
- Aggregations using GroupBy
- Summary statistics
- Correlation analysis
- Ranking analysis

---

## Visualizations

The project includes visualizations such as:

- Top Artists Bar Chart
- Artist Performance Index Ranking
- Playcount Comparisons
- Track Analytics Charts

---

## Future Improvements

- Automate daily data collection
- Power BI Dashboard
- Snowflake Integration
- Time-series trend analysis
- Predictive analytics

---

## Repository Structure

```
music-analytics-pipeline/
│
├── data/
├── music_analytics_pipeline.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Author

Sanskruti Vadakattu
