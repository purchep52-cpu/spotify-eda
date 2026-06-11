# 🎵 Spotify Tracks EDA

## Overview
Exploratory data analysis of 500k+ Spotify tracks to understand
what audio features drive song popularity.

## Key Findings
- **Danceability and loudnesss** has the strongest positive correlation with popularity (r = 0.06, 0.07)
- Instrumentalness has the strongest negative correlation to popularity
- **Acousticness** is negatively correlated - popular tracks are more produced
- Tempo contributes highly to whether a track is popular
- Metal genre is the highest in energy, followed by edm and rock while latin is the highest in danceability followed by hiphop and edm
- Classical genre is the lowest in energy and danceability
- This shows energy and danceability are related but not the same thing: a metal track can be high-energy but not danceable


## Tools Used
Python · pandas · seaborn · matplotlib · Google Colab

## Dataset
Spotify Tracks Dataset – Kaggle (maharshipandya) · ~600k rows

## Project Structure
spotify_eda.ipynb    ← Full analysis notebook \
/charts/             ← Exported visualisations
