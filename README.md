# Crypto Clustering Project

## Overview
This project applies K-means clustering to cryptocurrency data to identify distinct groups based on their characteristics. It further enhances the clustering process using Principal Component Analysis (PCA) to optimize the data's dimensionality before clustering.

## Steps and Key Findings

### 1. Data Preparation
The data is initially prepared and processed, making it suitable for clustering algorithms.

### 2. Clustering Cryptocurrencies
- **Using Original Data:** 
  - Method: K-means clustering
  - Optimal number of clusters (k): 4

- **Using PCA Optimized Data:** 
  - Method: Dimensionality reduction followed by K-means clustering
  - Total explained variance by the top three principal components: 89.5%
  - Optimal number of clusters (k): 4 (consistent with the original data)

### 3. Analysis and Visualization
Visual analysis is conducted to compare the cluster outcomes from the original and PCA-optimized data. The PCA optimization does not alter the optimal k value but leads to tighter clusters, specifically enhancing the grouping and clarity in clusters 0 and 3.

## Conclusion
The integration of PCA into the clustering process maintains the integrity of original clusters while achieving more concise and clearly defined clusters. This indicates the utility of PCA in improving clustering outcomes without significant changes to the data's underlying structure.

## Usage
- To replicate this analysis, ensure to install the necessary Python packages listed in `requirements.txt`.
- Run the Jupyter notebook to observe the clustering process and outcomes.

## Contributions
Contributions to this project are welcome. Please fork the repository and submit pull requests with suggested changes.
