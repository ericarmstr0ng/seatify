# Seatify
Seatify utilizes the spotify api to find the most featured artist on popular spotify playlists.


For the app to function you need to use the appropriate Client Credentials. This is easily done by using the following commands to set the enviornment variables:

export SPOTIPY_CLIENT_ID='your-spotify-client-id'

export SPOTIPY_CLIENT_SECRET='your-spotify-client-secret'

export SPOTIPY_REDIRECT_URI='your-app-redirect-url'

You can do this by create your credentials at: https://developer.spotify.com/documentation/web-api/

This application uses the spotipy wrapper and the openpyxl library:
https://github.com/plamere/spotipy

https://bitbucket.org/openpyxl/
