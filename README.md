# Playlist-Generator-Touchtunes

This project creates playlists for your library given a list of songs. It uses Markhov's Chain to predict what song to play next. The Intial distribution is px0 = (1 0 0 0 0) for the songs. (The song names are just numbers [1-5]). Selecting a song changes the probablity of every song appearing on the next generated playlist. In the current setting, it re-shuffles the playlist for a new sequence of songs. You can change the code and add an infinite list of songs to apply it to any song library. 

The code also generates a PMF to show how the songs ranked at the end of execution. 

The Librarys used for this project are: scipy.stats, numpy, math, matplotlib.pyplot and matplotlib inline.
