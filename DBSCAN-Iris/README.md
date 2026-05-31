# DBSCAN Clustering on Iris Dataset

## Overview
This project demonstrates the application of DBSCAN (Density-Based Spatial Clustering of Applications with Noise) on the Iris dataset. DBSCAN is an unsupervised clustering algorithm that groups data points based on density and identifies outliers as noise.

## Objectives
- Apply DBSCAN clustering on a real-world dataset.
- Standardize features for better clustering performance.
- Identify natural clusters in the Iris dataset.
- Detect noise points (outliers).
- Visualize clustering results.

## Dataset
**Iris Dataset**

- Contains measurements of iris flowers from three species.
- Features include sepal length, sepal width, petal length, and petal width.
- A standard dataset used for clustering and classification tasks.

**Source:**
Scikit-learn built-in dataset

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

## Methodology
1. Load the Iris dataset using `sklearn.datasets`.
2. Extract feature matrix.
3. Standardize features using `StandardScaler`.
4. Apply DBSCAN clustering algorithm.
5. Assign cluster labels to each data point.
6. Visualize clusters using first two features.
7. Identify unique clusters including noise points.

## Results
- DBSCAN successfully grouped the Iris dataset into multiple clusters.
- Noise points (label `-1`) were identified as outliers.
- Cluster distribution varies depending on `eps` and `min_samples` parameters.

## Key Learnings
- Understanding density-based clustering.
- Importance of feature scaling in clustering algorithms.
- Effect of DBSCAN hyperparameters on clustering results.
- Visualization of unsupervised learning results.

## Future Improvements
- Tune `eps` and `min_samples` for better clustering.
- Compare DBSCAN with K-Means and Hierarchical clustering.
- Use PCA for better visualization of clusters in 2D/3D.
