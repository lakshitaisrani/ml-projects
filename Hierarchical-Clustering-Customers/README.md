# Hierarchical Clustering on Mall Customers Dataset

## Overview
This project demonstrates **Hierarchical Clustering (Agglomerative Clustering)** on the Mall Customers dataset. The goal is to segment customers based on their annual income and spending score to identify meaningful customer groups.

A **dendrogram** is used to visualize the hierarchical structure and help decide the optimal number of clusters.

## Objectives
- Apply Hierarchical Clustering on customer data.
- Visualize customer distribution based on income and spending score.
- Use dendrogram to understand cluster formation.
- Perform Agglomerative Clustering.
- Segment customers into meaningful groups.

## Dataset
**Mall Customers Dataset (Kaggle)**

- Contains customer data from a shopping mall.
- Key features used:
  - Annual Income (k$)
  - Spending Score (1–100)
- Each row represents a unique customer.

**Source:** Kaggle dataset  
(shwetabh123/mall-customers)

## Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-Learn  
- SciPy  
- KaggleHub  

## Methodology

### 1. Load Dataset
- Dataset is downloaded using KaggleHub.
- Read CSV file into a pandas DataFrame.

### 2. Data Selection
- Selected features:
  - Annual Income (k$)
  - Spending Score (1–100)

### 3. Data Visualization
- Scatter plot created to visualize customer distribution.

### 4. Dendrogram Construction
- Used `linkage(method='ward')`
- Plotted dendrogram to analyze hierarchical relationships between customers.
- Helps determine optimal number of clusters.

### 5. Agglomerative Clustering
- Applied `AgglomerativeClustering`
- Number of clusters = 5
- Distance metric = Euclidean
- Linkage method = Ward

### 6. Final Visualization
- Customers grouped into clusters.
- Each cluster visualized using different colors.

## Results
- Customers are successfully segmented into 5 distinct groups.
- Dendrogram helps visualize hierarchical relationships.
- Clear separation between high and low spending customers.
- Useful for targeted marketing strategies.

## Future Improvements
- Try different linkage methods (single, complete, average).
- Optimize number of clusters using silhouette score.
- Extend analysis to full feature set.
- Compare with K-Means clustering results.
