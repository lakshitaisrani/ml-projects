# LDA on Cat and Dog Dataset

## Overview
This project demonstrates the application of Linear Discriminant Analysis (LDA) on a Cat and Dog image dataset. LDA is a supervised dimensionality reduction technique that projects data onto a lower-dimensional space while maximizing the separation between classes.

## Objectives
- Preprocess image data for machine learning.
- Apply LDA for dimensionality reduction.
- Maximize class separability between cats and dogs.
- Visualize the distribution of images in the reduced feature space.

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
7. Apply Linear Discriminant Analysis (LDA).
8. Project the data onto a one-dimensional discriminant axis.
9. Visualize the class separation between cats and dogs.

## Results
- Original feature dimension: 4096 features per image (64 × 64).
- Reduced feature dimension: 1 LDA component.
- Successfully projected image data into a lower-dimensional space while preserving class-discriminative information.
- Visualized the separation between cat and dog images along the LDA axis.

## Key Learning Outcomes
- Understanding supervised dimensionality reduction.
- Comparing LDA with PCA for feature extraction.
- Visualizing class separation in image datasets.
- Applying preprocessing techniques to image classification problems.

## Future Improvements
- Compare LDA and PCA performance on the same dataset.
- Train classification models using LDA-transformed features.
- Increase dataset size and evaluate the impact on class separation.
- Explore multi-class applications of LDA.
