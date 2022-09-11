# Spotify_Music_Analysis

Introduction : at first we managed to get the music data in Spotify, we got dataset named 
Spotify top music, which contains the top music that showed in the billboard from 2010 to 2019.
The data contained 584 song for 184 artist and 50 genres, as well as the song’s characteristics for 
example beats per minute, loudness of the song, acoustic ness, speechless, energy.
We then managed to make some statistics on the data, we draw the top artists popularity lifeline 
through out the years, and the correlations between the songs different characteristics, for example 
when the length of the song increases usually the popularity of the song decreases, and so on.
Predicting the popularity of the songs: predicting whether a song would make it and be a hit song or 
not, we used a plenty of models to test their accuracy and their ability to properly predict the song’s 
popularity. We finally used the SVM model, and its accuracy rate was 88%.
The most important features for the song to be popular are beats per minute and the energy.
Predicting the song’s genre : Predicting the genre of the song based on the song’s features 
(beats, loudness and etc. ), to predict the song’s genre we used another machine learning model 
,and its accuracy rate was quiet high.
Mood based playlist auto generator : we tried to replicate how Spotify divides a group of 
songs into multiple playlist based on the mood and the songs characteristics. Here we used 
clustering machine learning method to divide all the songs in the data set based on the similarities in 
their characteristics. The model divided the songs into multiple playlist, we looked for the 
commonalities between each song within the playlists 
A replica of Spotify recommendation system: we tried to replicate the 
recommendation system in Spotify we tried a couple of algorithms, we used API to access 
the Spotify user profile to retrieve the users playlists, and then apply this content-based 
recommendation system on each playlist. When applying this algorithm on multiple playlists 
from different genres and different music styles, and different time, the algorithm showed 
so relevant songs and the results were accurate and more precise and efficient than the 
Spotify recommendation system when dealing with Arabic classic songs from 1960, and also 
when dealing with English pop songs our model showed much more relative results than 
Spotify, which we are so proud of. (another dataset was used for this algorithm due to the 
need for bigger dataset to make more accurate recommendations, this dataset contained 
160k song from 1920 until now)
