# 🎧 Machine-Learning-Based-Spotify-Song-Clustering
This project uses unsupervised machine learning to group songs into clusters based on their audio features, aiming to replicate the logic behind curated Spotify playlists.

# Approach
  K-Means Clustering was applied to categorize songs based on features such as danceability, energy, key, loudness, liveness, valence, and tempo.

  The data was first scaled using MinMaxScaler to normalize feature values.

  The optimal number of clusters was determined using the Silhouette Method.

  Songs with similar characteristics were grouped into the same cluster by the K-Means algorithm.

  ![Image](https://github.com/user-attachments/assets/9d1c612a-32a5-447e-ae94-fcc6ec91c11a)

# Results
  The clustering model achieved a 70% match with actual Spotify playlists, demonstrating strong alignment between algorithmic clustering and human-curated playlists.

# 🔧 Technologies Used
  Python

  Scikit-learn

  Unsupervised Machine Learning (K-Means)
