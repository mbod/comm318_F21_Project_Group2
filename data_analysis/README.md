## Data analysis notebooks for COMM318 Final Project

The notebooks in this folder are where we extracted our datasets through Billboard and Spotify's APIs, cleaned the datasets, and performed a variety of analyses on the datasets. 

1) Data Collection Folder
- **Billboard Initial Data Collection, Observation, and Cleaning (2017, 2020, 2021).ipynb** uses Billboard's API to extract chart rankings from the Year-End Hot 100 in both 2017 and 2020. Then, it uses Spotipy to extract track-level metrics via Spotify's API, based on Spotify playlists of the Hot 100 in [2017](https://open.spotify.com/user/whe1998/playlist/255aUSCuVTcdD5JTogG69d?si=JCHWINVIRPiW3K_aGVzgcg), [2020](https://open.spotify.com/user/zoscar_/playlist/1WBljFutuk7uLQtfqfmjWV?si=DnFDuF-0SRuIfMVzPC6hOg), and [2021](https://open.spotify.com/user/11148724827/playlist/5Nt7KFSEfXIlsDIB8SCpNU?si=FuMmkxzlTKqHo8Vf9-BXtA). Both rankings and track-level metrics are merged together, and the datasets are then cleaned.
- **Spotify Initial 2017 Data Collection, Observation, and Cleaning.ipynb** uses Spotipy to extract track level metrics via Spotify's API from the official [Top Tracks of 2017: USA Playlist](https://open.spotify.com/user/spotify/playlist/37i9dQZF1DX7Axsg3uaDZb?si=IAEexkHXRTGnpkaGpZ0Fxw) before observing and cleaning the dataset.
- **Spotify Initial 2020 Data Collection, Observation, and Cleaning.ipynb** uses Spotipy to extract track level metrics via Spotify's API from the official [Top Tracks of 2020 USA Playlist](https://open.spotify.com/user/spotify/playlist/37i9dQZF1DXaqCgtv7ZR3L?si=eAq2hBqrTR-s5M99y-vQeQ) before observing and cleaning the dataset. 
- **Spotify Initial 2021 Data Collection, Observation, and Cleaning.ipynb** uses Spotipy to extract track level metrics via Spotify's API from the official [Top Tracks of 2021 USA Playlist](https://open.spotify.com/user/spotify/playlist/37i9dQZF1DXbJMiQ53rTyJ?si=GBsy_cPARumBOd1C_2es2w) before observing and cleaning the dataset. 


2) Rest of Folder 
- **Billboard vs. Spotify Data Analysis (2017, 2020, 2021).ipynb**: Comparing 2017, 2020, and 2021 Billboard chart data with 2017, 2020, and 2021 Spotify chart data, looking at danceability, energy, and duration metrics.  
- **Spotify Analysis 2020 (Step 1).ipynb**: Analyzing 2020 Spotify chart data (50-song dataset), looking at artist representation on the charts, mean metrics and songs which have the maximum level of various metrics, the distribution of durations and danceability levels, and explicitness. This was used more for exploratory purposes.
- **Spotify Analysis 2017 (Step 2).ipynb**: Analyzing 2017 Spotify chart data (98-song dataset), asking questions regarding danceability, duration, explicitness, tempo, acousticness, and artist representation. This was used more for exploratory purposes. 
- **Unique Song Analysis Spotify vs. Billboard.ipynb**: Collecting songs which only charted on either Billboard or Spotify in a particular year, running some year-based analyses on these 'unique' songs (i.e. comparing various metrics in songs which only charted on Spotify vs. only on Billboard), and creating two merged datasets for songs which only charted on 1) Spotify and 2) Billboard in 2017, 2020, and 2021. 
- **Merged Unique Song Analysis (Spotify vs. Billboard).ipynb**: General analysis on datasets containing Billboard-unique and Spotify-unique songs, conducting t-tests to assess significance and creating boxplots, finding correlations and doing cluster analyses between and on metrics. 

