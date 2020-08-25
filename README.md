# Pokemon EDA and quick Kmeans modelling

Jupyter notebook file to read data from a kaggle dataset (https://www.kaggle.com/mariotormo/complete-pokemon-dataset-updated-090420) containing a  .csv file with the list of the 890 known pokemon until 8th Generation and his varieties.

This project focuses on getting basic statistics on `stats` from all 8 generations of pokemon. There is a focuse on comparing mean values and distributions of `stats` over different generations.

A quick Kmeans model is built using scikit-learn to group all pokemons in separate clusters. After some dimensionality reduction, we end up with two clusters. 
* cluster 1 is called the slow-speed low-points cluster.
* cluster 2 is called the high-speed high-points one.

A simple function is defined to get the distribution of any classifier characterisitc in the two clusters (ex., which type or generation of pokemon is predominant in each cluster).
