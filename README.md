# MovieLens Recommender System (Unsupervised Learning)

## Overview
This project implements a personalized movie recommendation engine using the MovieLens dataset (100k+ ratings). It explores hidden user preference patterns through dimensionality reduction and clustering.

## Key Technical Features
* **Dimensionality Reduction:** Used **SVD (Singular Value Decomposition)** to identify 50 latent factors, capturing over 54% of data variance.
* **Clustering:** Implemented **KMeans** to segment users into 4 distinct preference groups based on their viewing history.
* **Recommendation Engine:** Built a system based on **Cosine Similarity** to suggest movies with high precision.
* **Data Preprocessing:** Handled sparse matrices and filtered data to ensure model stability and accuracy.

## Tech Stack
* Python (Pandas, NumPy, Scikit-learn, SciPy)
* Matplotlib & Seaborn (Data Visualization)
* SVD & KMeans (Machine Learning)
