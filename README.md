# Spotify Top Tracks Analysis

## Project Description

This project analyzes the top Spotify tracks dataset, which contains information about the top 50 songs on Spotify. The analysis includes data cleaning, exploratory data analysis, and insights into the characteristics of the most popular songs. [dataset](https://www.kaggle.com/datasets/atillacolak/top-50-spotify-tracks-2020).

Dataset content:
* artist: The name of the musician or band who performed the track.
* album: The title of the album containing the track.
* track_name: The name of the individual song.
* track_id: A unique identifier for the track, likely used by Spotify's system.
* energy: A measure from 0.0 to 1.0 representing the intensity and activity of the track.
* danceability: A measure from 0.0 to 1.0 indicating how suitable the track is for dancing.
* key: The key of the track, represented as an integer.
* loudness: The overall loudness of the track in decibels (dB).
* acousticness: A confidence measure from 0.0 to 1.0 of whether the track is acoustic.
* speechiness: A measure from 0.0 to 1.0 indicating the presence of spoken words in the track.
* instrumentalness: A measure from 0.0 to 1.0 representing the likelihood of a track containing no vocals.
* liveness: A measure from 0.0 to 1.0 detecting the presence of an audience in the recording.
* valence: A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track.
* tempo: The overall estimated tempo of a track in beats per minute (BPM).
* duration_ms: The duration of the track in milliseconds.
* genre: The musical category or style to which the track belongs.


### Technologies
* Python
* Jupyter Notebook
* Google Colab

### Python Libs
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-learn

## Getting Started
1. Clone this repository. 
2. Create virtual environment.
3. Install [requirements](requirements.txt).
4. Run [script](Spotify.ipynb) in Jupyter Notebook or Google Colab.
5. Raw Data is in [catalog](spotifytoptracks.csv).
