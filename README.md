# COMM-318 Final Project (F'21): What Makes Songs Popular on Spotify and Billboard?
## By Srinidhi Ramakrishna and Chris Chien

Welcome to our project!

As two musicians involved in a wide span of genres, both of us (Srinidhi and Chris) have always been interested in observing new trends in music. In just a few decades, we've noticed that the popular music landscape has changed dramatically in ways unthinkable just a few decades ago. 

With the rise of streaming services like Spotify and Apple Music, music is more accessible than it's ever been. At the same time, with new ways to listen to music, there are more ways to measure music popularity. Such streaming services have drastically transformed not just our music listening patterns, but marketing, creative, and artist approaches as well. We predict that as new technology and consumer patterns influence the music industry and how tracks achieve success, the musical characteristics of the songs which grow popular will change too.

This project will look at how musical characteristics in popular songs affect performance on two music charts: 

- The Billboard Year-End Hot 100, which is a yearly, more traditional, chart. It is the music industry standard for rating song popularity in the US, and has been ranking songs since the mid-1950s. The Billboard Hot 100 takes into account more old-fashioned metrics like physical song sales and radio play, and has incoporated streaming data since 2007.
- Spotify's yearly Top Tracks in the USA reports. These measure the most-streamed songs on Spotify in the US in a particular year, and naturally only take into account streaming numbers. 

To extract our datasets (found in the data folder), we utilized Billboard and Spotify's APIs. Billboard's API was used to extract chart rankings from the year-end Hot 100 in 2017, 2020, and 2021. Knowing that Spotify uses machine learning to collect track-level audio feature data on all songs, we used the Python library Spotipy to extract the features of the Hot 100 via Spotify's API and Spotify playlists which ordered all songs on this chart (Hot 100 in [2017](https://open.spotify.com/user/whe1998/playlist/255aUSCuVTcdD5JTogG69d?si=JCHWINVIRPiW3K_aGVzgcg), [2020](https://open.spotify.com/user/zoscar_/playlist/1WBljFutuk7uLQtfqfmjWV?si=DnFDuF-0SRuIfMVzPC6hOg), and [2021](https://open.spotify.com/user/11148724827/playlist/5Nt7KFSEfXIlsDIB8SCpNU?si=OVkxCLXiRxOzd3_iOsycHQ). 

Next, using Spotify's official [2017](https://open.spotify.com/user/spotify/playlist/37i9dQZF1DX7Axsg3uaDZb?si=IAEexkHXRTGnpkaGpZ0Fxw), [2020](https://open.spotify.com/user/spotify/playlist/37i9dQZF1DXaqCgtv7ZR3L?si=eAq2hBqrTR-s5M99y-vQeQ), and [2021](https://open.spotify.com/user/spotify/playlist/37i9dQZF1DXbJMiQ53rTyJ?si=ew2jD3DSQE2F-4Mywlu-6g) Top Tracks in the USA playlists, we again used Spotipy to collect the same audio data. All our data collection and cleaning is in the Data Collection subfolder in the data_analysis folder.

Our main question is – **Based on the audio metrics we have, are songs which chart on Spotify sonically different than songs which chart on Billboard and if so, how?**

We imagine this will be a fruitful analysis, given our knowledge of the debates surrounding music industry business practices. Indeed, we have a variety of supporting questions heading into the project. For example, given that radio edits of songs are always around 3 minutes, while TikTok's rise has encouraged short, catchy songs (and TikTok and Spotify are both [dominated](https://www.weareglacier.org/higher-education-marketing-blog/why-spotify-is-effective-in-reaching-gen-z) by young users), will songs popular on Spotify be shorter than songs popular on Billboard? Given songs popular on radio (think Top 40) tend to be peppy and crowd-pleasing, will songs popular on Billboard be more danceable and have higher valences than songs popular on Spotify? We'll look at these questions and more!

Our data_analysis folder tells the story of how this project developed. As you go through our notebooks, you see we first began by taking an exploratory look at some of our Spotify datasets. We then started to compare the Spotify and Billboard charts, in which results tended to be mixed - no strong differences between Spotify and Billboard charts appeared in our analyses. Then, we realized that song overlap between charts may be hiding any trends that do exist, so we conducted a unique song analysis, collecting songs which only appeared on one chart in a particular year and doing some yearly analyses. After merging this data and creating two datasets which consisted of songs which appeared only on Spotify or only on Billboard, we ran even more investigations, tried significance tests, and conducted a cluster analyses. 

Finally, we wrote a journalistic article covering our musical data story, found in the final_data_story folder. You can explore all our folders for more information on our data, data analysis, final story, and more. Thank you and we hope you enjoy our work!

- Srinidhi and Chris
