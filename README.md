# User Profile Clustering for Ads
This project applies clustering techniques to a user profile dataset to segment users for ad targeting. It explores several clustering algorithms and dimensionality reduction techniques.

## Dataset
The dataset (user_profiles_for_ads.csv) is expected to contain user features, including both numerical and categorical data.

## Techniques Used
Preprocessing: Standardization + One-Hot Encoding

Dimensionality Reduction: PCA and t-SNE

Clustering Models:

KMeans

Agglomerative Clustering

Gaussian Mixture Model (GMM)

Evaluation: Silhouette Score, Elbow Method

Visualization: Plotly, Yellowbrick, Matplotlib

## How to Run
1.Install dependencies:
pip install pandas numpy matplotlib seaborn scikit-learn yellowbrick plotly

2.Place your dataset as user_profiles_for_ads.csv in the working directory.

3.Run the notebook or Python script:
python your_script_name.py

## Output
Optimal cluster count via Elbow Method

Cluster visualizations with PCA/t-SNE

Evaluation scores for each model

## Future Work
Integrate DBSCAN

Add cluster labeling interpretation

Deploy with Streamlit for interactive analysis
