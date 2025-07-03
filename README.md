# spotify-eda-python
# 🎧 Spotify Streaming EDA - Python Project

## Overview
This project analyzes the most streamed songs on Spotify in 2024. Using Python and pandas, we explore the features that influence a song’s popularity.

## Dataset
- Source: Kaggle – "Most Streamed Spotify Songs 2024"
- 4,600 songs, multiple platforms: Spotify, YouTube, TikTok, Apple Music

## Tools Used
- Python
- pandas
- seaborn
- matplotlib
- Jupyter Notebook

## Key Steps
- Data cleaning (removing commas, converting text to numbers)
- Removing irrelevant columns
- Correlation heatmap
- Explicit vs Non-explicit songs
- Trends by release date

## Insights
- Strong correlation between playlist reach and stream count
- TikTok exposure significantly boosts popularity
- Recent releases dominate the top of the charts

## Files
- `spotify_analysis.ipynb` – main notebook
- Graphs folder – visualizations
## Key Steps
- Data cleaning: removed commas, converted text columns to numeric
- Dropped irrelevant or empty columns
- Analyzed correlations using `df.corr()` and seaborn heatmap
- Explored differences between Explicit and Clean songs
- Identified trends by Release Year

## Insights
- Strong correlation between playlist reach and stream count
- TikTok plays have a noticeable impact on a song’s popularity
- Clean songs perform just as well (if not better) than explicit tracks
- Newer songs (2023–2024) dominate the top charts

## Files
- `spotify_analysis.ipynb` – main Python notebook
- `Most Streamed Spotify Songs 2024.csv` – dataset from Kaggle
- `graphs/` – folder with PNG images of key charts

## Author
Rinat Leibovich  
[LinkedIn Profile](https://www.linkedin.com/in/rinat-leibovich)
