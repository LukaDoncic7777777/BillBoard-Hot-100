# Overview
This is a Python project that mainly scraps the 100 Billboard popular songs within a given year. Users can provide a certain date and have the certain 100 songs be added to their private songlists,
if the song is not found in Spotify, it will automatically skip the song. Moreover, I am utilizing the spotipy module for getting user_id and scraping the Spotify song uri for a list of songs. And the 
SpotifyOAuth module is for verifying the Client-id and Client-secret. When user run this project, he can automatically add a year of user's choice billboard songs into his personal private playlist.
