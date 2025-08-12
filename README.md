# Customer Segmentation Analysis

## Project Overview
This project leverages unsupervised machine learning (K-Means and Hierarchical Clustering) to segment customers based on their purchasing behavior and demographic data. The goal is to enable data-driven marketing strategies by identifying distinct customer groups.

## Key Features

### 1. Hierarchical Clustering Approach
-   **Dendrogram Analysis**: Determines optimal clusters via hierarchical linkage.
-   **Agglomerative Clustering**: Builds a tree-based segmentation model.
-   **Dimensionality Reduction**: Uses PCA for interpretable visualizations.

### 2. K-Means Clustering Approach
-   **Data Preprocessing**: Handles missing values, encodes categorical features, and normalizes data.
-   **Clustering**: Applies K-Means to group customers into meaningful segments.
-   **Evaluation**: Uses metrics like the Silhouette Score to assess cluster quality.
-   **Visualization**: Employs PCA for 2D/3D cluster visualization.

## Business Applications
-   **Targeted Marketing**: Tailor promotions based on customer segments.
-   **Customer Retention**: Identify high-value and at-risk groups.
-   **Sales Optimization**: Adjust strategies per segment behavior.

## Technical Implementation
-   **Language**: Python
-   **Libraries**: Scikit-learn, Pandas, Matplotlib, Seaborn
-   **Data**: Structured customer data (e.g., purchase history, demographics)
