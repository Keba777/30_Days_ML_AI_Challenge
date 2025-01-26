# Day 11: Principal Component Analysis (PCA)

## What I Learned
- **Principal Component Analysis (PCA)**:
  - How PCA works as a dimensionality reduction technique by transforming data into principal components.
  - The importance of variance explained by each component.
  - Visualization of high-dimensional data in a reduced space.
- **MNIST Dataset**:
  - Preprocessing and feature scaling for applying PCA.
  - Understanding the structure of MNIST, a dataset for handwritten digit recognition.

## Tasks Completed
1. **Data Loading and Preprocessing**:
   - Loaded the MNIST dataset.
   - Normalized the dataset to ensure features are on the same scale.
2. **Dimensionality Reduction**:
   - Applied PCA to reduce the dimensionality of MNIST data from 784 features to 2 components.
   - Calculated the explained variance ratio for the two components.
3. **Visualization**:
   - Visualized the 2D scatter plot of MNIST data based on the two principal components.
   - Analyzed the separation of digits in the reduced space.

## Resources Used
- [PCA Overview](https://scikit-learn.org/stable/modules/decomposition.html#pca)
- [MNIST Dataset](https://www.openml.org/d/554)
- [PCA in Scikit-Learn](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)
- [Data Visualization with Matplotlib](https://matplotlib.org/stable/users/index.html)
- [Guide to Dimensionality Reduction](https://towardsdatascience.com/an-introduction-to-dimensionality-reduction-for-machine-learning-80ed1f6db58b)
