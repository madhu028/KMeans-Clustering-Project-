# KMeans Clustering Project

This repository contains an example project for performing unsupervised learning using K-Means clustering on the Mall Customers dataset.

## Structure

- `data/`: Place your dataset CSV here (`Mall_Customers.csv`).
- `notebooks/`: Jupyter notebook demonstrating data loading, preprocessing, elbow method, clustering, and visualization.
- `src/`: Python script version of the clustering code.
- `results/`: Saved plots and evaluation results.

## Usage

1. Clone this repository.
2. Place the `Mall_Customers.csv` file inside the `data/` folder.
3. Install dependencies:

4. Run the notebook in `notebooks/kmeans_clustering.ipynb` or run the Python script in `src/kmeans_clustering.py`.

## Notes

- The project uses PCA to reduce features to 2D for visualization.
- Elbow method helps select the optimal number of clusters.
- Silhouette Score is used to evaluate clustering quality.

