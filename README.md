## 🧬 Clustering and Principal Component Analysis (PCA)

**Problem Statement**:  
Apply unsupervised learning techniques, including PCA for dimensionality reduction and clustering models to identify hidden patterns in the data. Evaluate clustering performance and analyze transformed feature space.

**Data**:  
- Source: Titanic dataset from kaggle [`Titanic`](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- Description: Numerical features appropriate for clustering analysis and dimensionality reduction.

**Data Mining Operations**:  
- Loaded clustering dataset into Pandas dataframes.
- Performed data preprocessing: normalized features, handled missing values.
- Split data into training and testing subsets.
- Applied Principal Component Analysis (PCA):
  - Reduced feature dimensionality while preserving variance.
  - Fit PCA on training data and transformed both training and testing sets.
- Clustering:
  - Applied clustering models (e.g., K-Means) on the PCA-transformed data.
- Evaluated clustering performance using cluster accuracy scores and visualized cluster separations.
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

**Model Outputs**:  
- PCA transformation plots illustrating variance explained by principal components.
- Scatter plots of clustered data in reduced 2D space.
- Accuracy scores measuring clustering performance against known labels (where available).

**Limitations**:  
- Clustering depends heavily on the choice of number of clusters (k) and the distribution of data.
- PCA may lead to information loss if too few principal components are selected.

**Were you able to effectively solve the problem?**  
Yes, dimensionality reduction and clustering provided meaningful visualizations and groupings of the data, showing effective use of unsupervised learning techniques.

