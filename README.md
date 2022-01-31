# Using Machine Learning to Generate Music Recommendations
### Ria Sinha
### Capstone Java Final Project

In this project, I will implement a KNN clustering algorithm to group together different songs based on similar audio features. A user can input a list of songs and the model will then recommend similar songs by computing the cosine distance between each of the vectorized features. <br />

How to:
- **Run Code**: Call the recommend_songs(song_list, spotify_data, n_songs=10) function <br />
""" Returns a list of recommended songs that are similar to the inputted songs

    Parameters:
    song_list (dict): A dictionary of songs and their corresonding release year
    spotify_data (pandas.core.frame.DataFrame): A dataframe of all downloaded songs and their corresponding features
    n_songs (int): Number of songs to recommend

    Returns:
    rect (list): A list of dictionaries that include a song and its release year as the key, value pair

   """
- **Interpret Output**: Running the recommend_songs method will produce a list of songs that are similar to the input songs<br />

Sources: 
- **NumPy:** https://numpy.org/doc/
- **Pandas:** https://pandas.pydata.org/docs/
- **Scikit-learn:** https://scikit-learn.org/stable/
- **Data:** https://www.kaggle.com/vatsalmavani/music-recommendation-system-using-spotify-dataset/data
