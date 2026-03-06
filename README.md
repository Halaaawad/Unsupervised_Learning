# Unsupervised_Learning
The assignment focuses on dimensionality reduction techniques (PCA and Autoencoders), clustering algorithms (K-Means and Gaussian Mixture Models), and their evaluation using various metrics. The dataset used for this assignment is the Breast Cancer Wisconsin (Diagnostic) dataset, which aims to identify patterns and groupings to distinguish between malignant and benign tumors.

## Objectives
1. Implement dimensionality reduction techniques (PCA and Autoencoders) from scratch using NumPy.
2. Implement clustering algorithms (K-Means and Gaussian Mixture Models) from scratch using NumPy.
3. Evaluate clustering performance using internal and external validation metrics.
4. Analyze the impact of dimensionality reduction techniques on clustering performance.
5. Perform statistical validation and comparison of different approaches.

## PCA (Principal Component Analysis)
1. Implement full eigenvalue decomposition approach
2. Include explained variance ratio calculation
3. Implement reconstruction error computation
4. Support inverse transform (reconstruction)

## Autoencoder 
1. Implement a fully connected autoencoder with:
- At least 3 hidden layers in encoder and decoder
- Customizable bottleneck dimension
- Multiple activation functions (ReLU, sigmoid, tanh)
2. Implement backpropagation from scratch
3. Include training with mini-batch gradient descent
4. Implement learning rate scheduling
5. Add regularization (L2)

## K-Means Clustering
1. Implement K-Means++ initialization
2. Include random initialization for comparison
3. Implement convergence criteria (tolerance-based and max iterations)
4. Track and report inertia history

## Gaussian Mixture Models (GMM)
1. Implement full EM algorithm from scratch
2. Support all covariance types: full, tied, diagonal, spherical
3. Include log-likelihood computation
4. Implement convergence monitoring
5. Add numerical stability handling (avoid singular matrices)

# Experimentation
We conduct 6 experiments where we first implement K-Means and GMM on the original data and then implement both again once after performing PCA and another time after Autoencoder
