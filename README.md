# Can We Predict Billboard Hot 100 Songs?

A standard metric of a song's popularity in the U.S. is its appearance (or not) and its ranking on the [*Billboard* Hot 100](https://www.billboard.com/charts/hot-100) chart. This weekly list ranks the songs based on their album sales, radio airplay, and online streaming statistics in the U.S. 

![alt text](https://github.com/jieunchoi/billboard100_hit_or_not/blob/master/img/example_featss.png)

Objective: Examine the characteristics of popular songs released between 2010-2018 using the [Spotify audio features](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/). The data---e.g., danceability, energy, acousticness, and tempo---are obtained using [Spotipy](https://spotipy.readthedocs.io/en/latest/), a Python library for accessing and interacting with the Spotify API. Try to classify a song as a Hot 100 hit (*ongoing part of the project*).

The project notebook can be viewed online [here](https://nbviewer.jupyter.org/github/jieunchoi/billboard100_hit_or_not/blob/master/hitornot.ipynb) at https://nbviewer.jupyter.org/.