## Data files for COMM318 Final Project

This folder contain the data files we have used in our analysis, separated into two subfolders - "Raw", which contains all the original, unedited data, and "Clean", which contains all the data after it has been edited for clarity for analysis. 

Raw:
- spotify2021raw.csv contains the raw, uncleaned track-level metrics gathered using Spotipy based on the songs in the official [Top Tracks of 2021 USA Playlist](https://open.spotify.com/user/spotify/playlist/37i9dQZF1DXbJMiQ53rTyJ?si=1FayZNYIQc2i4lp1WMe5eQ). 
- spotify2020raw.csv contains the raw, uncleaned track-level metrics gathered using Spotipy based on the songs in the official [Top Tracks of 2020 USA Playlist](https://open.spotify.com/user/spotify/playlist/37i9dQZF1DXaqCgtv7ZR3L?si=eAq2hBqrTR-s5M99y-vQeQ). 
- spotify2017raw.csv contains the raw, uncleaned track-level metrics gathered using Spotipy based on the songs in the official [Top Tracks of 2017: USA Playlist](https://open.spotify.com/user/spotify/playlist/37i9dQZF1DX7Axsg3uaDZb?si=IAEexkHXRTGnpkaGpZ0Fxw). 
- billboard2021.csv contains song rankings for the Billboard Year-End Hot 100 chart in 2021, merged with raw, uncleaned track-level metrics for those songs based on a [Spotify playlist](https://open.spotify.com/user/11148724827/playlist/5Nt7KFSEfXIlsDIB8SCpNU?si=_Xcb6PPZRFqryddQrfMTwQ) with the same tracks.
- billboard2020.csv contains song rankings for the Billboard Year-End Hot 100 chart in 2020, merged with raw, uncleaned track-level metrics for those songs based on a [Spotify playlist](https://open.spotify.com/user/zoscar_/playlist/1WBljFutuk7uLQtfqfmjWV?si=DnFDuF-0SRuIfMVzPC6hOg) with the same tracks.
- billboard2017.csv contains song rankings for the Billboard Year-End Hot 100 chart in 2017, merged with raw, uncleaned track-level metrics for those songs based on a [Spotify playlist](https://open.spotify.com/user/whe1998/playlist/255aUSCuVTcdD5JTogG69d?si=JCHWINVIRPiW3K_aGVzgcg) with the same tracks.

Clean:
- spotifytop2021cleaned.csv contains the same tracks/rows as spotify2021raw.csv, although some cleanup (column removal and renaming, unit conversions) has been applied. 
- spotifytop2020cleaned.csv contains the same tracks/rows as spotify2020raw.csv, although some cleanup (column removal and renaming, unit conversions) has been applied. 
- spotifytop2017cleaned.csv contains the same tracks/rows as spotify2017raw.csv, although the same cleanup (column removal and renaming, unit conversions) has been applied.
- spotifyonly_allyears.csv contains songs which only appeared on the Spotify charts, but not the Billboard charts of that year, across 2017, 2020, and 2021.

- billboard2021cleaned.csv contains the same tracks/rows as billboard2021.csv, although similar cleanup as those in the Spotify datasets has been applied to clean up the Spotify track-level metrics.
- billboard2020cleaned.csv contains the same tracks/rows as billboard2020.csv, although again, similar cleanup as those in the Spotify datasets has been applied to clean up the Spotify track-level metrics.
- billboard2017cleaned.csv contains the same tracks/rows as billboard2017.csv, although again, similar cleanup as those in the Spotify datasets has been applied to clean up the Spotify track-level metrics.
- billboardonly_allyears.csv contains songs which only appeared on the Billboard charts, but not the Spotify charts of that year, across 2017, 2020, and 2021.

