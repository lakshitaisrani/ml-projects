# K-Means Clustering on Iris Dataset

## Overview
This project demonstrates the application of **K-Means Clustering**, an unsupervised machine learning algorithm, on the Iris dataset. The model groups similar data points into clusters without using labeled outputs and helps identify hidden patterns in the data.

Additionally, the **Elbow Method** is used to determine the optimal number of clusters.

## Objectives
- Apply K-Means clustering on the Iris dataset.
- Group similar data points into clusters.
- Visualize clustering results.
- Identify cluster centroids.
- Use the Elbow Method to find optimal number of clusters.

## Dataset
**Iris Dataset (Scikit-Learn)**

- Contains 150 samples of iris flowers.
- 4 features:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- 3 species (not used in training):
  - Setosa
  - Versicolor
  - Virginica

**Source:** Scikit-learn built-in dataset

## Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-Learn  

## Methodology

### 1. Load Dataset
- Load Iris dataset using `sklearn.datasets`.

### 2. Apply K-Means Clustering
- Set number of clusters = 3
- Fit the model on dataset
- Assign cluster labels to each data point

### 3. Identify Centroids
- Compute cluster centers
- Visualize centroids using “X” marker

### 4. Visualization
- Plot first two features:
  - Sepal length
  - Sepal width
- Color points based on cluster labels

### 5. Elbow Method
- Run K-Means for k = 1 to 10
- Compute WCSS (Within-Cluster Sum of Squares)
- Plot WCSS vs number of clusters
- Identify optimal cluster value (elbow point)

## Results
- Data successfully grouped into 3 clusters.
- Cluster centroids clearly represent group centers.
- Visualization shows clear separation among clusters.
- Elbow method helps confirm optimal number of clusters.

## Future Improvements
- Apply PCA before clustering for better visualization.
- Try different distance metrics.
- Compare with hierarchical clustering and DBSCAN.
- Evaluate clustering using silhouette score.
