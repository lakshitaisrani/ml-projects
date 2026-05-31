# SVD on MNIST Digits Dataset

## Overview
This project demonstrates the application of Singular Value Decomposition (SVD) using `TruncatedSVD` on the MNIST-like Digits dataset. SVD is used to reduce the dimensionality of image data while preserving the most important patterns, enabling easier visualization and analysis of high-dimensional data.

## Objectives
- Apply Singular Value Decomposition (SVD) to image data.
- Reduce dimensionality from 64 features to 2 components.
- Visualize handwritten digits in a lower-dimensional space.
- Understand how SVD captures variance in data.
- Analyze clustering patterns of different digit classes.

## Dataset
**Digits Dataset (Scikit-Learn)**

- Contains 8×8 grayscale images of handwritten digits (0–9).
- Each image is flattened into a 64-dimensional feature vector.
- Total samples: 1797 images.

**Source:** Scikit-learn built-in dataset

## Technologies Used
- Python
- NumPy
- Matplotlib
- Scikit-Learn

## Methodology
1. Load the digits dataset from `sklearn.datasets`.
2. Visualize sample digit images.
3. Flatten image data into feature vectors.
4. Apply TruncatedSVD for dimensionality reduction.
5. Reduce 64-dimensional data to 2 components.
6. Transform the dataset using SVD.
7. Visualize the reduced data using a scatter plot.
8. Analyze explained variance ratio.

## Results
- Successfully reduced 64-dimensional digit data to 2D space.
- Clear clustering patterns observed for different digit classes.
- Similar digits show slight overlap in reduced space.
- SVD preserved important structure while simplifying visualization.
- Explained variance ratio shows how much information each component retains.

## Future Improvements
- Compare SVD with PCA for dimensionality reduction performance.
- Experiment with different numbers of components (2, 10, 20, etc.).
- Use reduced features for classification tasks.
- Apply on larger datasets like full MNIST.
