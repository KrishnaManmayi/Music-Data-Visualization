# Music-Data-Visualization
Performed music data visualization using python-seaborn library and matplotlib library on FMA dataset

## About:
Visualizing and Analyzing music data, comparison of tracks based on genres and audio features.
This work presents the visualization of music data which includes variety of information regarding music albums, tracks, genres of tracks, features of data (echonest / spotify features of music) and also audio features extracted from the python library librosa.
Plots depicting the relationship between genre and the interest of listeners in a particular genre were visualized. Comparison of music tracks categorized by genres was done based on the sounding which was understood by the features Acousticness and liveness; the kind of instruments used which contributes to the feature instrumentalness, the amount of energy and danceability involved in the song, and also speechiness, tempo and valence involved in the music. The above mentioned features are calculated and provided by echonest (Now called as Spotify).
Genres with same parents and genres which are very distinct were grouped and the features were compared. Analysis of audio signal features of music tracks was done by extracting the features using the librosa library among which spectral features are primarily used. Few of these features are the spectral centroid, frequencies, band width, the mel-frequencies, chromograms, spectral contrast etc..How these features vary for different genres is visualized and genre detection is done using machine learning classification techniques. Performance of various classifiers on music data is compared and analyzed.

Data Source: 
https://github.com/mdeff/fma
https://arxiv.org/abs/1612.01840


## Reference:
@inproceedings{fma_dataset,
  title = {{FMA}: A Dataset for Music Analysis},
  author = {Defferrard, Micha\"el and Benzi, Kirell and Vandergheynst, Pierre and Bresson, Xavier},
  booktitle = {18th International Society for Music Information Retrieval Conference (ISMIR)},
  year = {2017},
  archiveprefix = {arXiv},
  eprint = {1612.01840},
  url = {https://arxiv.org/abs/1612.01840},
}
