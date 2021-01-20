# Python-Projects
Install dependencies
`pip install spotipy` 
`pip install plotly`
## What it does
The following program webscrapes the latest list of 200 hits from Billboard and retrives additional information about each track as well as audio features.  Initially, the program scrapes and allocates each artist name, as well as the song title, into a data frame called ``df_billboard``. Then, by using Spotify API, the program loops through each row and sends requests to retrieve information including track_uri, album, release date, popularity, and audio features. The information is subsequently appended into a data frame designated as ``df_spotify``. After all of the requests have been completed, both data frames are merged using .concat function and saved as CSV files. 
