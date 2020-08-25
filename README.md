# billboard-spotify

## Resume
Project developed to scraping billboard top 100 and automate my playlists

## tools
 - Python, Jupyter Notebook, Panda, BeautifulSoup, spotipy, Tableau

## data source
- songs list : https://www.billboard.com/charts/year-end
- songs features: api-spotify

## scraping
The information was initially collected on the Billboard website in a category classified as the 100 most successful songs of the year, ranging from 2006 to 2019.
In this first step, the name of the song, the artist, the year and the rank were collected.
After data collection, the main featurings artist were separated.
With the songs and artist names, a conection to spotify was made through the spotipy library. There was possible to search for characteristics of the songs such as Duration, Danceability, Energy and others.

## playlist
It was applied a filter of the top 3 song for each year and creating playlist on spotify.
https://open.spotify.com/playlist/2rPBxFieJMmRYKcxZeX9JG?si=mLTV0n5qQ7u7CnRzUfKAUA

## analysis
For a overview of data the data collected it was used Tablau as tool.
https://public.tableau.com/profile/guilherme6477#!/vizhome/IRONHACK-PROJETO3/BILLBOARD-SPOTIFY?publish=yes

## issues
Some songs and artists searched through the code were not found, leaving some data incomplete.


## future resolutions
Improve code to get more data in spotify-api.
