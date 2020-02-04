# Data Science Project: Trendspotting on Spotify

## Team
The Pandas of Jupyter

## **Team Members**
* Atul | anulkar| Nulkar
* Justin | justinjapan | McSpadden
* Jasmine | jasmineorr | Orr
* Keith | keithhorbin | Horbin
* Stone | stonega1992 | Powell

## Project Goals/Research Questions to Answer
Explore Spotify's Playlists across different Genres of music and understand various relationships and trends between Artists, Songs & their Audio Features:
1. Which Genres are more popular than others? Statistically, are there significant differences in popularity between Genres?
2. How do various Audio Features of a Song such as it's Danceability, Energy, Liveness, etc., influence the popularity of Songs?
3. How are popular songs trending in terms of their valence, i.e. songs that sound more positive (e.g. happy, cheerful, euphoric), vs songs that sound more negative (e.g. sad, depressed, angry)? Is there any correlation between the speechiness and the valence of a song?
3. Does the duration of a song affect it's position within a playlist?
4. Does the position of a song in a playlist impact it's popularity?
5. Are singles more popular than albums or compilations?

## Dataset Sources
* Artists, Playlists, Tracks and Music Metadata sourced using the [Spotify Web API](https://developer.spotify.com/documentation/).
* CSV files exported using the API and which were used in our analysis can be found [here](https://github.com/anulkar/DataScience-Project1/tree/master/datasets).

## Jupter Notebooks
* [spotify_exploration.ipynb](https://github.com/anulkar/DataScience-Project1/blob/master/spotify_exploration.ipynb) - contains code to retrieve and wrangle data using the Spotify web APIs and generate some basic stats/plots.
  * To run the notebook, you will need a Spotify developer account with your own `client_id` and `client_secret` credentials to authenticate the API requests. Generate your client credentials from the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications).
  * Once you have setup your credentials on the Dashboard, create an `api_keys.py` file in your local repository and copy the following lines of code, so that your credentials are imported automatically in the jupyter notebook.
    ```python
    spotify_client_id = 'your client_id goes here'
    spotify_client_secret = 'your client_secret goes here'
    ```
* [spotify_analysis.ipynb](https://github.com/anulkar/DataScience-Project1/blob/master/spotify_analysis.ipynb) - contains code to perform more in-depth analysis of the Spotify data and to seek answers to our research questions.