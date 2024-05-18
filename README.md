# Project: Most Streamed Spotify Songs 2023 🎵
![Unknown](https://github.com/IraSafonik/project_Most-Streamed-Spotify-Songs-2023/assets/32171563/1233206f-8365-4e98-bf62-d6ad9213d62c)

# About Spotify
Spotify is a Swedish music streaming and media services provider where users can listen to their Favourite Artists, Songs and Albums.Founded in 2006, the company mainly provides an audio streaming platform, the "Spotify" platform, that offers DRM-restricted music and podcasts from record labels and media companies. As a freemium service, basic features are free with advertisements or automatic music videos. Additional features, such as offline listening and commercial-free listening, are offered via paid subscriptions.

# About Dataset

## Description :
This dataset contains a comprehensive list of the most famous songs of 2023 as listed on Spotify. The dataset offers a wealth of features beyond what is typically available in similar datasets. It provides insights into each song's attributes, popularity, and presence on various music platforms. The dataset includes information such as track name, artist(s) name, release date, Spotify playlists and charts, streaming statistics, Apple Music presence, Deezer presence, Shazam charts, and various audio features.

## Key Features:
- track_name: Name of the song
- artist(s)_name: Name of the artist(s) of the song
- artist_count: Number of artists contributing to the song
- released_year: Year when the song was released
- released_month: Month when the song was released
- released_day: Day of the month when the song was released
- in_spotify_playlists: Number of Spotify playlists the song is included in
- in_spotify_charts: Presence and rank of the song on Spotify charts
- streams: Total number of streams on Spotify
- in_apple_playlists: Number of Apple Music playlists the song is included in
- in_apple_charts: Presence and rank of the song on Apple Music charts
- in_deezer_playlists: Number of Deezer playlists the song is included in
- in_deezer_charts: Presence and rank of the song on Deezer charts
- in_shazam_charts: Presence and rank of the song on Shazam charts
- bpm: Beats per minute, a measure of song tempo
- key: Key of the song
- mode: Mode of the song (major or minor)
- danceability_%: Percentage indicating how suitable the song is for dancing
- valence_%: Positivity of the song's musical content
- energy_%: Perceived energy level of the song
- acousticness_%: Amount of acoustic sound in the song
- instrumentalness_%: Amount of instrumental content in the song
- liveness_%: Presence of live performance elements
- speechiness_%: Amount of spoken words in the song

## Potential Use Cases:
- Music analysis: Explore patterns in audio features to understand trends and preferences in popular songs.
- Platform comparison: Compare the song's popularity across different music platforms.
- Artist impact: Analyze how artist involvement and attributes relate to a song's success.
- Temporal trends: Identify any shifts in music attributes and preferences over time.
- Cross-platform presence: Investigate how songs perform across different streaming services.

# Overview

![-🌍 Regional Variations-purple](https://github.com/IraSafonik/project_Most-Streamed-Spotify-Songs-2023/assets/32171563/faf64499-84e2-4c9a-ba1d-efc23409daa8)
Gathering and processing Spotify data for trends analysis

![-📊 Data Collection-blue](https://github.com/IraSafonik/project_Most-Streamed-Spotify-Songs-2023/assets/32171563/99c2d3ea-7704-4cf4-bf40-5cf23ec5acdd)
Analyzing the popularity and shifts in music genres

![-📁 Playlist Dynamics-red](https://github.com/IraSafonik/project_Most-Streamed-Spotify-Songs-2023/assets/32171563/a20f3b02-29d5-4a36-82e2-f8e1eb351ac7)
Spotlight on trending and emerging artists

![-👩‍🎤 Artist Highlights-orange](https://github.com/IraSafonik/project_Most-Streamed-Spotify-Songs-2023/assets/32171563/e5d45641-928a-4d25-b294-94cea9c67786)
Examining changes in playlist creation and curation

![-🎶 Genre Trends-green](https://github.com/IraSafonik/project_Most-Streamed-Spotify-Songs-2023/assets/32171563/8970fe2c-329b-4f2f-aca4-11fadbb76df6)
Identifying regional variations in music preferences

# Conclusions Based on the Dataset Analysis

### Conclusion Based on Mode Distribution:
<img width="480" alt="Знімок екрана 2024-05-16 о 17 59 08" src="https://github.com/IraSafonik/project_Most-Streamed-Spotify-Songs-2023/assets/32171563/f8f4e041-e3d9-4cd8-8fad-042e381a3c22">  <img width="697" alt="Знімок екрана 2024-05-16 о 18 01 23" src="https://github.com/IraSafonik/project_Most-Streamed-Spotify-Songs-2023/assets/32171563/ddff8404-1d10-4290-9016-750622c29473">

#### From the dataset, we observe the following distribution of the mode of the songs:
- Major: 550 songs (57.71%)
- Minor: 403 songs (42.29%)

This indicates that a majority of the popular songs from 2023 are in a major key, which is often associated with happy, bright, and upbeat music. Conversely, a significant portion of the songs are in a minor key, typically linked with more somber, introspective, or moody tones. The nearly balanced presence of both major and minor modes suggests a diverse musical landscape, catering to a wide range of emotional experiences for the listeners.

### Top 10 Artists by Song Count:
<img width="971" alt="Знімок екрана 2024-05-16 о 17 54 35" src="https://github.com/IraSafonik/project_Most-Streamed-Spotify-Songs-2023/assets/32171563/bf100af7-f57d-4ce5-8f5e-1d36839f6633">

- Taylor Swift: 34 songs
- The Weeknd: 22 songs
- Bad Bunny: 19 songs
- SZA: 19 songs
- Harry Styles: 17 songs
- Kendrick Lamar: 12 songs
- Morgan Wallen: 11 songs
- Ed Sheeran: 9 songs
- BTS: 8 songs
- Feid: 8 songs

Taylor Swift stands out as the most prolific artist in this dataset with 34 songs, significantly ahead of the others. This highlights her dominant presence in the music industry in 2023. The Weeknd, Bad Bunny, and SZA also show a strong presence with 22, 19, and 19 songs respectively, reflecting their significant influence and popularity. Harry Styles follows with 17 songs, while Kendrick Lamar and Morgan Wallen each have over 10 songs, indicating their strong fan bases and consistent output.

Ed Sheeran, BTS, and Feid, with 9 and 8 songs respectively, round out the top 10, showing that these artists also had a substantial impact on the music scene in 2023. The diversity in genres and styles among these top artists reflects the varied tastes of music listeners today.

### Top 10 Years and Mounths by Song Release Count
<img width="969" alt="Знімок екрана 2024-05-16 о 17 57 56" src="https://github.com/IraSafonik/project_Most-Streamed-Spotify-Songs-2023/assets/32171563/8f56918f-d3bd-40a4-981c-64b7834a01e3">

#### Top 10 Years by Song Release Count:
- 2022: 402 songs
- 2023: 175 songs
- 2021: 119 songs
- 2020: 37 songs
- 2019: 36 songs
- 2017: 23 songs
- 2016: 18 songs
- 2014: 13 songs
- 2013: 13 songs
- 2015: 11 songs

#### Top 10 Months by Song Release Count:
- 1: 134 songs
- 5: 128 songs
- 3: 86 songs
- 6: 86 songs
- 11: 80 songs
- 12: 75 songs
- 10: 73 songs
- 4: 66 songs
- 7: 62 songs
- 2: 61 songs

Top Years: The distribution of song releases by year shows the trend in music production, with 2022 having the highest count at 402 songs, followed by 2023 with 175 songs. This reflects ongoing musical activity and the prominence of recent hits in these years.

Top Months: The distribution of releases by month indicates seasonal trends in music releases, with January (134 songs) and May (128 songs) showing higher activity. This could be due to strategic release timing by artists and record labels.

### Conclusions Based on the Descriptive Statistics for Energy Percentage by Artist Count 
<img width="971" alt="Знімок екрана 2024-05-16 о 17 59 30" src="https://github.com/IraSafonik/project_Most-Streamed-Spotify-Songs-2023/assets/32171563/3bfc0b5d-48c0-498e-8905-7e791a4107a3">

#### Insights: 
#### Energy Percentage Trends:
| Artist Count | Count | Mean Energy Percentage | Standard Deviation | Range     | Median (50th percentile) |
|--------------|-------|------------------------|--------------------|-----------|---------------------------|
| 1            | 587   | 62.12%                 | 17.45              | 9% to 97% | 63%                       |
| 2            | 254   | 67.62%                 | 14.46              | 30% to 97%| 69%                       |
| 3            | 85    | 67.96%                 | 14.32              | 25% to 93%| 68%                       |
| 4            | 15    | 66.07%                 | 15.47              | 44% to 86%| 73%                       |
| 5            | 5     | 71.80%                 | 14.06              | 51% to 87%| 72%                       |
| 6            | 3     | 75.33%                 | 4.16               | 72% to 80%| 74%                       |
| 7            | 2     | 60.00%                 | 21.21              | 45% to 75%| 60%                       |
| 8            | 2     | 72.00%                 | 5.66               | 68% to 76%| 72%                       |

Songs with a single artist have a lower average energy percentage (62.12%) compared to songs with multiple artists. This might indicate that solo performances tend to have more varied energy levels, possibly due to a broader range of musical styles.
The energy percentage generally increases as the number of contributing artists increases, with a peak mean energy percentage of 75.33% for songs with six artists.
Consistency in Energy Levels:

The standard deviation for energy percentage decreases as the number of artists increases, especially noticeable for songs with more than four artists. This suggests that songs with more artists tend to have more consistent energy levels.
Notably, songs with six artists have the lowest standard deviation (4.16), indicating very similar energy levels across these tracks.
Range of Energy Levels:

The range of energy levels is widest for solo artist tracks (9% to 97%), reflecting greater variability in solo performances.
For groups with more artists, the range becomes narrower, indicating that collaborative efforts might lead to more harmonized and consistent energy outputs.
Median Energy Levels:

The median energy percentage increases with the number of artists, with songs involving five or six artists showing the highest median energy levels (72% and 74%, respectively).
This indicates that collaborative songs tend to maintain a higher baseline energy compared to solo tracks.

#### Summary:
The analysis reveals that songs with more contributing artists generally exhibit higher and more consistent energy percentages. Solo performances, while having a broader range of energy levels, tend to have a lower average energy. This could be due to the diverse nature of solo artists' music compared to the potentially more harmonized output of collaborative tracks. These insights can be valuable for understanding how the number of contributing artists influences the overall energy and consistency of popular songs.

### Conclusions Based on Correlation Heatmap
<img width="972" alt="Знімок екрана 2024-05-16 о 17 55 01" src="https://github.com/IraSafonik/project_Most-Streamed-Spotify-Songs-2023/assets/32171563/e027b702-3e53-4603-9556-8ddc1e2cb81d">

#### Based on the correlation heatmap, the following conclusions can be drawn:
- Some attributes have weak correlation: For example, artist_count does not exhibit significant correlation with most other features in the dataset, except for a weak correlation with danceability_% and valence_%.

- Some attributes show moderate correlation: For instance, released_year demonstrates moderate correlation with some other attributes such as in_spotify_playlists, in_apple_playlists, and in_deezer_charts.

- Some attributes exhibit strong correlation: For example, energy_% and valence_% show moderate correlation with each other, suggesting that energetic songs may have a more positive mood.

# Summary 
### Based on the analysis performed, several overarching conclusions can be drawn:

#### Dataset Overview: 
The dataset covers various music industry aspects comprehensively, including song features, artist details, release information, and platform presence.

#### Key Players and Tracks: 
Certain artists like Taylor Swift and The Weeknd, along with specific tracks such as "Daylight" and "Take My Breath," stand out due to their high frequency in the dataset. This indicates their significant influence and popularity during the analyzed period.

#### Temporal Trends: 
Recent years, notably 2023, see a substantial increase in song releases, reflecting a dynamic music scene during this period.

#### Correlation Insights: 
Correlation analysis reveals varying degrees of association between attributes, guiding the identification of influential factors driving overall trends.

#### Analytical Potential: 
The dataset offers ample opportunities for deeper exploration, such as genre preferences, regional variations, and the impact of song features on popularity.

### In summary, 
the numerical insights provide valuable guidance for strategic decision-making in the music industry and serve as a basis for further detailed analysis.
