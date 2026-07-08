# 🎵 Spotify Streaming Analysis Dashboard | Power BI

An interactive Power BI dashboard built to analyze Spotify listening history and uncover meaningful insights into music consumption patterns, listening behavior, and user engagement.

---

## Project Overview

Music streaming platforms generate vast amounts of listening data every day. This project transforms raw Spotify listening history into an interactive Business Intelligence dashboard that enables users to explore listening trends, identify favorite artists and albums, analyze listening habits, and compare performance over time.

The dashboard combines data modeling, Power Query transformations, DAX calculations, and interactive visualizations to answer real-world business questions.

---

## Business Problem

The objective of this project is to answer questions such as:

- How has music listening changed over time?
- Which albums, artists, and tracks are listened to most frequently?
- How does listening differ between weekdays and weekends?
- What are the peak listening hours?
- How does listening activity compare between the latest year and the previous year?
- Which tracks receive high engagement based on listening duration and play frequency?

---

## Dashboard Pages

### 📈 Overview
<img width="1128" height="745" alt="image" src="https://github.com/user-attachments/assets/94518b42-a48e-4105-8228-05e2d5b3c9d6" />

Provides a high-level summary of listening activity.

Features include:

- Total Albums Played
- Total Artists Played
- Total Tracks Played
- Listening Trends Over Time
- Latest Year vs Previous Year Comparison
- Year-over-Year Growth
- Weekday vs Weekend Analysis
- Top 5 Albums
- Top 5 Artists
- Top 5 Tracks
- Interactive Filters

---

### 🎧 Listening Patterns

<img width="558" height="373" alt="image" src="https://github.com/user-attachments/assets/29e11f71-6117-4e25-8684-2d00cd879c95" />

Explores user listening behavior through interactive visualizations.

Features include:

- Listening Hours Heatmap
- Hour vs Day Analysis
- Average Listening Time
- Track Frequency Analysis
- Scatter Plot with Dynamic Parameters
- Quadrant Analysis

---

### 📋 Details

<img width="557" height="370" alt="image" src="https://github.com/user-attachments/assets/8905d8db-783b-4b8e-afb2-806162d9b13f" />

Provides a detailed tabular view of the dataset.

Features include:

- Album Details
- Artist Details
- Track Details
- Listening Time
- Interactive Drill-Down
- Exportable Data View

---

## Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- CSV Dataset

---

## Power BI Features Used

- Data Modeling
- Calendar Table
- Relationships
- Power Query Transformations
- Drill Down
- Interactive Filters
- Bookmarks
- Navigation Buttons
- Conditional Formatting
- Matrix Visualization
- Heatmap
- Scatter Plot
- Dynamic Parameters

---

## DAX Highlights

The report includes several advanced DAX techniques including:

- DISTINCTCOUNT
- VAR
- CALCULATE
- DIVIDE
- ALLSELECTED
- MINX
- MAXX
- SWITCH
- FORMAT
- GENERATESERIES
- SELECTEDVALUE
- Dynamic Year-over-Year KPIs
- Dynamic Min/Max Detection
- Time Intelligence

---

## Key Insights

The dashboard highlights several notable listening patterns:

- Listening activity reached its highest level around **2021**, followed by a gradual decline in subsequent years.
- **Weekday listening consistently accounts for a larger share of total listening activity** than weekend listening across albums, artists, and tracks.
- **The Beatles** emerged as the most frequently played artist, while albums such as **Past Masters**, **Abbey Road**, and **The Wall** rank among the most listened-to albums.
- Listening activity is concentrated during the **evening hours**, indicating that music consumption is highest later in the day.
- The listening heatmap shows that **listening behavior remains fairly consistent across weekdays**, with stronger activity during evening and late-night hours.
- The scatter plot indicates that **most tracks have relatively short average listening durations but are replayed frequently**, while only a small number of tracks combine both high listening time and high play frequency.
- Year-over-year KPI cards enable quick identification of increases or declines in album, artist, and track engagement.


---

# Recommendations

Based on the observed listening patterns:

- Prioritize recommendations featuring artists and albums with consistently high replay frequency, such as The Beatles.
- Schedule music recommendations and notifications during peak evening listening hours to maximize engagement.
- Highlight highly replayed tracks in personalized playlists, as they represent strong user preferences.
- Investigate tracks with long listening durations but low replay frequency, as these may represent niche interests worth surfacing to similar listeners.
- Continue monitoring year-over-year listening trends to identify changes in user engagement over time.

---

# Repository Contents

| File | Description |
|------|-------------|
| **Spotify Streaming Analysis Dashboard.pbix** | Power BI dashboard |
| **Spotify Streaming Analysis Dashboard.pdf** | Exported dashboard report |
| **spotify_history.csv** | Dataset used for analysis |
| **Business Requirements.pdf** | Project objectives and business requirements |
| **README.md** | Project documentation |
| **LICENSE** | MIT License |

---

## Future Improvements

Potential enhancements include:

- Artist Drill-Through Pages
- Dynamic Insight Cards
- Mobile Dashboard Layout
- Streaming Platform Comparison
- Genre-Based Analysis
- Playlist Analytics

---

## Author

**Simran Kirtania**

Aspiring Data Analyst passionate about transforming raw data into actionable business insights using SQL, Python, Excel, and Power BI.

