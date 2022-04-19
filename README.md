# SpotifyAnalysis

## About
This is our DSAI Mini-project for CE1115 (Introduction to Data Science and Artificial Intelligence). We look to explore Spotify's hit songs and find songs that fell through the filter. Songs that had the potential to become hits judging by their popularity and their audio features but somehow failed to do so. We took our 3 Spotify datasets from [Kaggle](https://www.kaggle.com/).

## Contributors
- @WB99 - Data Preparation, Exploratory Data Analysis, The Underrated
- @gohxuezhe - The Overlooked, The Ones that Got Away

## Problem Definition
Everyone's raving to the newest hit single by the hottest artist. Shopping malls and eateries only play the most trending and most hip songs. Don't we all get tired of those songs after a while? We want to know what makes a song popular, and beyond that a chart topper - and then proceed to flip all of that upside down. We want to uncover the overlooked, misunderstood and underrated, songs that deserve to be played, down supermarket aisles and up on-air. Here's to the undervalued songs!

1. What audio features do hit songs usually have?
2. Create a playlist, The Overlooked -> songs that were very popular but somehow did not make it into the hit list
3. Create a playlist, The Ones that Got Away -> songs that had the audio features typical of that of hit songs but did not make it into the hit list
4. Create a playlist, The Underrated -> songs that had the audio features typical of popular songs but did not make it into the hit list

## Models Used
1. Classification Tree
2. Linear Regression
3. K-Nearest Neighbour Classifier
4. Grid Search CV

## Conclusion
- Hit songs generally have higher popularity but there are popular songs that did not make it as a hit
- There isn't any audio feature that will accurately determine whether a song will become a hit. But hit songs are generally more positive and provide good energy
- No audio feature tested has a strong correlation with popularity but loudness is strongly correlated with energy while both have strong negative correlation with acousticness

Our playlists:
[The Overlooked](https://open.spotify.com/playlist/6Ul5P7JtKkS89F52Sa9zGe?si=a2d0f6c22a654851)
[The Ones that Got Away](https://open.spotify.com/playlist/6zOj6hJJng6f1f2d0uYRhp?si=77aaabd69e884a28) ~_Editor's pick_~
[The Criminally Underrated](https://open.spotify.com/playlist/5i5HAFOlSRARd9PPkSwNDw?si=562486d999af4a75)

## Learnings from this project
- Increasing Classifier Tree's depth does not necessarily increase classification accuracy and runs the risk of overfitting
- K-Nearest Neighbour, Random Forest Classifier, Grid Search CV
- Random Over Sampling and Random Under Sampling
- Spotify API call 

## References
[Spotify API](https://developer.spotify.com/console/post-playlist-tracks/)
[K-Nearest Neighbour](https://towardsdatascience.com/predicting-popularity-on-spotify-when-data-needs-culture-more-than-culture-needs-data-2ed3661f75f1#:~:text=According%20to%20Spotify,%20%E2%80%9Cpopularity%20is,a%20lot%20in%20the%20past.%E2%80%9D)
[Random Forest](https://datatofish.com/random-forest-python/)
[Random Forest v.s. Decision Tree](https://www.kdnuggets.com/2022/02/random-forest-decision-tree-key-differences.html)
[Stack Overflow](https://stackoverflow.com/)
