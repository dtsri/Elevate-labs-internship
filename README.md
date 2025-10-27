# YouTube Trend Video Analytics Project

## Overview
This project analyzes the YouTube trending videos dataset for India, focusing on patterns in engagement, top channels, and key trends. The analysis includes data cleaning and transformation using Python, with interactive dashboarding in Power BI.

## Dataset
- **Source:** [Kaggle - Trending YouTube Video Statistics (INvideos.csv)](https://www.kaggle.com/datasets/datasnaek/youtube-new?select=INvideos.csv)
- **Features:** Video metadata, engagement metrics (views, likes, comments), trending/publish dates, categories, and channel data.

## Tools Used
- **Python (pandas, matplotlib, seaborn):** Data cleaning, EDA, initial analysis
- **Power BI:** Data modeling, calculated measures (DAX), dashboard creation

## Data Processing & Analysis
- Loaded raw CSV, removed duplicates, handled missing values
- Converted date columns and engineered features (e.g., month, year, time to trend)
- Analyzed key metrics: average/max views, comments, likes; unique channels; top categories
- Explored temporal, channel, and category-based trends in engagement

## Dashboard Highlights
- **KPI Cards:** Total trending videos, unique channels, average/max engagement
- **Bar Charts:** Top 10 channels, top 5 categories (with avg likes)
- **Line Charts:** Monthly/yearly trends in avg views and likes
- **Scatter Plot:** Correlation between views and likes
- **Matrix/Table:** Channel-wise engagement by month
- **Filters:** For exploring specific channels or categories

## Key Findings
- Entertainment and news dominate Indian YouTube trending topics
- Certain channels (e.g., VikatanTV) trend very frequently
- Strong correlation between views, likes, and comments
- No strong monthly or weekly trend patterns, but quick "time to trend" for many top videos

## How to Use
1. Clone/download this repo
2. Open the Power BI file to interact with the dashboard
3. Explore the notebook to see the cleaning and analysis workflow

## Credits
- Data: Kaggle (original creators)
- Analysis & Dashboard: [Your Name]

