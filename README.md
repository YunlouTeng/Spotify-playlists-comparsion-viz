## Spotify-playlists-comparsion-viz: Project Overview

[For the Interactive version dashboard](https://public.tableau.com/app/profile/jake6334/viz/spotify_playlists_workbook/Dashboard1)
![alt text](https://github.com/YunlouTeng/Spotify-playlists-comparsion-viz/blob/main/Dashboard_.png)

* **Interesting findings**:

  * My playlist's audio feature score[^1] is above average when compared to TOP50 USA, but it lacks popularity[^2]. Furthermore, it encompasses a wider range of features than both TOP50 USA and TOP50 Taiwan.
  
  * For listeners in the USA, a distinct preference for upbeat, high-energy tracks, with a average danceability and energy score surpassing 62% and 60% repectively. Topping the list of most danceable tracks was Mac DeMarco's "Heart to Heart" with a score of 90%, while Bebe Rexha's "I'm Good(Blue)" emerged as the most energetic track with a score of 97%.
  
  * For Listeners in Taiwan, oringinal soundtracks of TV shows are fairly popular, which inevitably contributes to the lowest liveness scores of 15%.
  

[^1]: For Danceability, Energy, Liveness, Speechiness: 0% represents the possible lowest, while 100% represents the possible highest.
[^2]: Predicted by Spotify.


## Code and Resources Used

**Python Version**: 3.8

**Modules**: numpy, pandas, sklearn, seaborn, spotipy

**Tools**: Google Colab, Tableau

**Inspirations**:https://medium.com/@paigevsmyth/day-35-box-whisker-plots-for-spotify-audio-features-4e175c0a7b18

**Resources**:https://developer.spotify.com/documentation/web-api/reference/#/operations/get-track



