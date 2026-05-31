# PCA on Cat and Dog Dataset

## Overview
This project demonstrates the use of Principal Component Analysis (PCA) for dimensionality reduction on a Cat and Dog image dataset. Images are converted into grayscale, resized, flattened into feature vectors, and transformed using PCA to reduce the number of dimensions while preserving important information.

## Objectives
- Preprocess image data for machine learning.
- Apply PCA to high-dimensional image features.
- Reduce computational complexity by lowering feature dimensions.
- Visualize the dataset in a two-dimensional PCA space.

## Dataset
**Dog and Cat Classification Dataset**

- Contains images of cats and dogs.
- Images are converted to grayscale and resized to 64×64 pixels.
- A subset of 500 cat images and 500 dog images is used for analysis.

**Source:**  
https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset

## Technologies Used
- Python
- NumPy
- OpenCV
- Matplotlib
- Scikit-Learn
- KaggleHub

## Methodology
1. Download the dataset using KaggleHub.
2. Load cat and dog images.
3. Convert images to grayscale.
4. Resize images to 64×64 pixels.
5. Flatten images into feature vectors.
6. Standardize the data using StandardScaler.
7. Apply PCA with 50 principal components.
8. Visualize the dataset using the first two principal components.

## Results
- Original feature dimension: 4096 features per image (64 × 64).
- Reduced feature dimension: 50 principal components.
- Generated a 2D PCA visualization showing the distribution of cat and dog images.

## Files
- `pca_cat_dog.ipynb` – Complete implementation of PCA on the Cat and Dog dataset.

## Future Improvements
- Train classification models using PCA-transformed features.
- Compare PCA with LDA and other dimensionality reduction techniques.
- Experiment with different image sizes and numbers of principal components.
