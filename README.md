# K-Means-Spotify-Song-Clustering

The goal of this project is to cluster a dataset of Spotify songs based on various features, such as danceability and energy, and analyze the resulting clusters. The dataset is loaded into a Pandas dataframe and preprocessed by cleaning and normalizing the values and selecting a subset of the columns to use in the clustering process. This helps to ensure that the clustering process is performed on clean, standardized data.

A clustering algorithm, such as K-means or hierarchical clustering, is then chosen and the appropriate number of clusters is determined using a method such as the elbow method. This helps to ensure that the number of clusters is not too small or too large for the dataset.

The clustering model is fit to the preprocessed dataset and the clusters are generated. The quality of the clusters is evaluated using evaluation metrics such as the silhouette score and the clusters are visualized by projecting the data onto a 2D space and coloring the data points according to their cluster assignment. This helps to see how well the clusters represent the underlying data and how they differ from each other.

The silhouette score was 0.1248. A silhouette score close to 0 can indicate that the clusters are not well-defined and that the data points within each cluster are not very similar to each other. This can be due to a variety of factors, but one possibility is that the features you are using to perform the clustering are not sufficiently descriptive of the underlying data. However, since songs can be in genres and subgenres, it's possible that these labels may not be very informative for certain songs. This is because genres and subgenres can be somewhat interchangeable and may not always accurately reflect the characteristics of a particular song.
 
The clusters can then be used for further analysis, such as examining the characteristics of the individual clusters or using the cluster assignments as features in other machine learning models. If a hierarchical clustering algorithm was used, a dendrogram can also be created to visualize the hierarchy of the clusters. This helps to see the relationships between the clusters and how they are related to each other.

The data came from Kaggle's [Spotify 1.2M+ Songs Dataset](https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs).
