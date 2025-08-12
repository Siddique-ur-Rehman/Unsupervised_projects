# Customer Segmentation Project

This project performs customer segmentation using hierarchical clustering on a dataset containing customer information. The goal is to identify distinct groups of customers based on their characteristics and behavior.

## Project Steps:

1.  **Data Loading and Exploration**: The customer data is loaded and initial checks for duplicates and missing values are performed.
2.  **Data Preprocessing**: Missing income values are imputed, and categorical features (Education and Marital_Status) are encoded using Label Encoding.
3.  **Hierarchical Clustering**: Agglomerative clustering is applied to segment the customers. The number of clusters is determined by examining the dendrogram.
4.  **Dimensionality Reduction**: Principal Component Analysis (PCA) is used to reduce the data to 2 dimensions for visualization purposes.
5.  **Visualization**: The customer segments are visualized in a 2D scatter plot based on the principal components.

## Files:

-   `customer_segmentation.csv`: The dataset used for customer segmentation.
-   `requirements.txt`: Lists the Python dependencies required to run the project.
-   `README.md`: Provides an overview of the project.

## How to Run:

1.  Clone the repository.
2.  Install the required dependencies using `pip install -r requirements.txt`.
3.  Run the Jupyter notebook or Python script containing the code.

This project provides valuable insights into customer behavior and can be used for targeted marketing strategies and personalized customer experiences.
