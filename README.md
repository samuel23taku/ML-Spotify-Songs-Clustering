
# Clustering song data from Spotify top songs data

## 1. Overview
This project involves the analysis and clustering of songs from the Spotify Top 200 charts, starting from 2016. The dataset includes various attributes of the tracks, such as the number of streams, weeks on the chart, and detailed audio features (e.g., tempo, key, danceability). The technical information is sourced from the Spotify Web API.
More details about the dataset's construction can be found [here](https://www.kaggle.com/datasets/julianoorlandi/spotify-top-songs-and-audio-features)

## 2. Libraries

- sklearn
- numpy
- pandas

## 3. Algorithms

- Principal Component Analysis (PCA): To reduce the dimensionality of the dataset and identify the primary components explaining the variance in the data.
- K-Means Clustering: To segment the songs into distinct clusters based on their audio features.


## 4. Summary

After performing thorough data cleaning and preprocessing, PCA was applied to reduce the data to its most significant components. K-Means clustering was then used to identify three distinct clusters within the dataset, providing insights into the underlying patterns and groupings of the top songs.

By understanding these clusters, we can gain a deeper understanding of the characteristics that define popular tracks on Spotify and how they differ from one another.