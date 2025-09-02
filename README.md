# EDA_Project_Spotify

## Project Overview

This project explores the **Spotify Tracks dataset** using **Exploratory Data Analysis (EDA)** and **Machine Learning techniques**.The goal is to uncover hidden patterns in music features, analyze trends across genres and artists, and apply **clustering algorithms (K-Means)** to group songs into meaningful categories.

## Tech Stack

* Python 3.12
* Pandas / NumPy for data manipulation
* Matplotlib / Seaborn for visualization
* Scikit-learn for scaling and clustering
* Jupyter Notebook for interactive analysis

## Objectives

* Perform data cleaning and preprocessing on the Spotify dataset
* Explore audio features such as danceability, energy, valence, and tempo
* Identify trends across artists, albums, and release years
* Cluster songs based on audio features to find “musical similarity groups”
* Generate insights that could be useful for playlist generation or recommendation systems

## Dataset

* **Dataset Used**: `data.csv` (Spotify Songs Dataset from Kaggle)
* **Source**: [Spotify Tracks Dataset on Kaggle](https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db?utm_source=chatgpt.com)
* **Description**: Subset of the Spotify API dataset containing track metadata and audio features.
* **Key Columns**:

  * `track_name` – Name of the song
  * `artist_name` – Artist of the song
  * `album` – Album title
  * `release_year` – Year of release
  * `popularity` – Spotify popularity score
  * Audio Features: `danceability`, `energy`, `tempo`, `valence`, `acousticness`, `instrumentalness`, etc.

## EDA Highlights (Planned)

* Distribution of audio features
* Trends in audio features across years
* Most frequent artists and albums in the dataset
* Correlations between features (heatmaps, pairplots)

## Clustering Approach

* Features scaled using **StandardScaler**
* Songs grouped into **k=4 clusters** with KMeans
* Each cluster represents a potential “style” of music based on audio characteristics

## Future Work

* Experiment with other clustering methods (DBSCAN, Hierarchical Clustering)
* Build a basic **playlist recommender** based on cluster proximity
* Deploy findings in an interactive **Streamlit dashboard**
