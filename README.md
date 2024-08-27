### Mini-Spotify-Project
The project consisted of downloading data from the Spotify platform, with a particular focus on extracting and preparing information about albums, artists and songs on a particular playlist. The main objective of the project was to collect and organise the data for further analysis.

To achieve this, access to the Spotify API was configured using the spotipy library and appropriate access keys. 

The collected data was then extracted and processed. Album information such as ID, name, release date, track count and URL was stored as a DataFrame and a duplicate removal process was applied. Similarly, artist (ID, name, URL) and song (ID, name, duration, URL, popularity, date added, album ID, artist ID) data was processed and organised into DataFrames. Dates have been converted into the appropriate datetime formats.

The project provides a dataset that forms the basis for a detailed analysis of the playlist structure on Spotify.
