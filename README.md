# Can We Predict Billboard Hot 100 Songs?

A standard metric of a song's popularity in the U.S. is its appearance (or not) and its ranking on the [*Billboard* Hot 100](https://www.billboard.com/charts/hot-100) chart. This weekly list ranks the songs based on their album sales, radio airplay, and online streaming statistics in the U.S. 

![alt text](https://github.com/jieunchoi/billboard100_hit_or_not/img/energy_danceability.png)

Objective: predict whether or not a song appeared on the Hot 100 between 2010-2018 using the [Spotify audio features](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/). This data set---e.g., danceability, energy, acousticness, and tempo---are downloaded using [Spotipy](https://spotipy.readthedocs.io/en/latest/), a Python library for accessing and interacting with the Spotify API. We examine factors determining a song's popularity, train our binary classifier using the 2010-2018 data, and finally, for fun, try to predict the Hot 100 status for songs released in 2019.

The project notebook can be viewed online [here](https://nbviewer.jupyter.org/github/jieunchoi/billboard100_hit_or_not/blob/master/hitornot.ipynb) at https://nbviewer.jupyter.org/.