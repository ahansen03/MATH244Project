This is the folder in which we will save all of our data used for the project.

# Data Source

The hits/nonhits datasets were collected from [MusicOSet](https://marianaossilva.github.io/DSW2019/updates.html). MusicOSet data was collected by researchers using the Spotify API and Billboard Hot 100 data.

The nonhits dataset is particularly large, so we uploaded a csv file of the first 100 rows to this Github folder.

# Codebook

1. "duration_ms": The length of the track (in milliseconds).
2. "acousticness": The measure of how acoustic a track is. Ranges from 1.0 (high acousticness) to 0.0 (low acousticness).
3. "danceability": The measure of how suitable a track is for dancing based on a multiple musical elements including tempo, rhythm stability, beat strength, and overall regularity. Ranges from 1.0 (high danceability) to 0.0 (low danceability).
4. "energy": The measure of how intense and active a song is based on multiple musical elements including tempo, density/timbre, loudness, and others. Ranges from 1.0 (high energy) to 0.0 (low energy).
5. "instrumentalness": The measure of how instrumental a song is (as opposed to vocal). Ranges from 1.0 (no vocals, high instrumentalness) to 0.0 (vocals, low instrumentalness). Values above 0.5 indicate instrumental tracks, with confidence increasing as it approaches 1.
6. "liveness": Detects the presence of an audience in a track. Ranges from 1.0 (very likely a live track) to 0.0 (highly unlikely to be a live track).
7. "loudness": The perceived loudness of a song, measured in decibels (dB). Typically ranges from -60 dB to 0 dB.
8. "speechiness": Detects the level of spoken word in a track (e.g. audiobook, podcast, news clip). Ranges from 1.0 to 0.0. Values above 0.66 indicate tracks that are made entirely of spoken words. Values between 0.33 and 0.66 indicate tracks that have a mix of music and spoken word. Values below 0.33 indicates music and other non-spoken word tracks.
9. "valence": The measure of how "positive" a track is. Range from 1.0 (high valence, positive) to 0.0 (low valence, negative). 
10. "tempo": The musical "speed" of a track, in beats per minute (BPM).
11. "key": The estimated overall key of the track. Integers map to pitches using standard Pitch Class notation. If no key was detected, the value is -1. Otherwise ranges from 0 (key of C) to 11 (key of B).
13. "explicit": A boolean indicating if a song is tagged as being explicit in Spotify (TRUE if yes, FALSE if no).
14. "mode": The indicator of what kind of scale was used. Can be 1 (major scale) or 0 (minor scale).
15. "hit": A boolean indicating if a song reached the Billboard Hot 100 (TRUE if yes, FALSE if no).
