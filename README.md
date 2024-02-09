# 2023 Spotify Most Streamed Music Analysis

## This project provides an analysis carried out on 953 tracks on Spotify to determine the most streamed songs, artistes with the highest streams, top tracks in playlists, as well as other relevant metrics.

##  Gathering & Cleaning

The data used in this project was sourced from [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023). The data was sourced as a CSV file and was cleaned in Excel - ensuring there are no duplicates, using appropriate data types, and deleted unwanted columns. The dataset was also transformed to concatenate three columns containing year, month, and date, to a single date column. After cleaning and transformation was completed, the data was loaded to Power BI for analysis and visualization.

## Top 10 Songs and Top 10 Artistes

The top performing songs and artistes and streams were visualized using a stacked row chart. Also, the sum of other metrics such as total number of streams, number of artistes, number of tracks, and period of time covered were also shown using cards. 

![](

## Yearly Trend of Streams

I decided to carry out a time analysis to show how the trend of streams recorded on the platform from 1930 til date. Since the period covered spans across 93 years, I used the SWITCH function to create a DAX that groups the years in 10s. This way, I was able to show the trend of streams recorded across different range of years.

![](

## Top Tracks in Playlists

Data was provided on how the tracks are performing in other playlists like Spotify playlist, Apple playlist, and Deezer playlist. The Top 3 tracks in each of these playlists were visualized. These numbers represent the number of Spotify, Apple, and Deezer playlists these songs were included in. For instance, for Spotify playlist, "Get Lucky - Radio Edit" which comes top is included in 52.9K Spotify playlists.

Visualizations were also done to show the top songs in terms of danceability, valence, and energy. Danceability defines how suitable the song is for dancing, Valence is the positivity of the song's musical content, while Energy represents the perceived energy level of the song.

![](h

## Remarks

Some of the insights I generated are stated below:

- **Best Performing Track:** "Blinding Lights" by The Weeknd is the best performing track. The song was released in 2019 and has recorded 3.7 billion streams. The track is included in 672 Apple playlists, the highest number than any other track.
- **Best Performing Artiste:** The Weeknd is the artiste with the highest number of streams. The Weeknd has 14.2 billion streams followed closely by Taylor Swift with 14.1 billion streams.
- **Years with the highest number of streams:** The trend analysis shows that songs released from 2021 to 2023 have the highest number of streams - 216 billion, even with a shorter time range. Following closely are tracks released between 2011 to 2020 with 205.3 billion streams.
