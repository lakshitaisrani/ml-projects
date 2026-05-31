# Feature Selection using Forward Selection and Backward Elimination (Iris Dataset)

## Overview
This project demonstrates feature selection techniques using **Sequential Feature Selection (SFS)** on the Iris dataset. Feature selection helps in identifying the most important features that contribute to model performance while reducing complexity.

Two methods are implemented:
- Forward Selection
- Backward Elimination

## Objectives
- Understand feature selection techniques in machine learning.
- Apply Forward Selection to choose best features.
- Apply Backward Elimination to remove least important features.
- Compare selected features from both methods.
- Improve model efficiency by reducing feature space.

## Theory

### Feature Selection
Feature selection is the process of selecting the most important features from a dataset.

It helps:
- Improve model performance  
- Reduce overfitting  
- Reduce computation time  

### 1. Forward Selection
Forward Selection starts with no features and adds features one by one based on model performance improvement.

### 2. Backward Elimination
Backward Elimination starts with all features and removes the least important features one by one until the best subset remains.

## Dataset
**Iris Dataset (Scikit-Learn)**

- Contains 150 samples of iris flowers.
- 4 features:
  - sepal length
  - sepal width
  - petal length
  - petal width
- 3 target classes:
  - Setosa
  - Versicolor
  - Virginica

**Source:** Scikit-learn built-in dataset

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  

## Methodology

### Forward Selection
1. Load Iris dataset.
2. Initialize a Linear Regression model.
3. Apply `SequentialFeatureSelector` with `direction='forward'`.
4. Select best 2 features based on model performance.
5. Display selected feature names.

### Backward Elimination
1. Start with all features.
2. Apply `SequentialFeatureSelector` with `direction='backward'`.
3. Iteratively remove least important features.
4. Select best 2 features.
5. Display selected feature names.

## Results
- Forward Selection selected the most impactful features by gradually adding them.
- Backward Elimination removed less important features step-by-step.
- Both methods returned optimal subsets of features.
- Reduced feature space improved interpretability and efficiency.

## Future Improvements
- Try different number of selected features.
- Compare results with PCA and SVD.
- Use classification models instead of Linear Regression.
- Evaluate model accuracy after feature selection.
