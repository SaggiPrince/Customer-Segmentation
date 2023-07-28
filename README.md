# Customer Segmentation for Mall Shopping Behavior Analysis
This project uses customer clustering techniques to identify distinct customer segments based on their annual income and spending score. The results of the clustering can be used by the mall to improve its marketing strategies and customer experience.

## Introduction
The goal of this project is to identify distinct customer segments based on their annual income and spending score. This information can be used by the mall to improve its marketing strategies and customer experience.

# The methodology:

The project will be conducted in the following steps:

- **Data Preprocessing:** The initial step involves loading the dataset and handling any missing values.
  
- **Feature Scaling:** To ensure fair clustering based on all features, we standardize the data using StandardScaler.
  
- **Elbow Point Graph:** The Elbow method is employed to identify the optimal number of clusters for KMeans clustering. This method plots the Within-Cluster Sum of Squares (WCSS) against the number of clusters and helps us select an appropriate number of clusters.
  
- **Silhouette Analysis:** Silhouette analysis is performed to validate the quality of clustering. It calculates a silhouette score for each cluster, indicating how well-separated the clusters are.
  
- **Cluster Comparison with Box Plots:** The income distribution for each cluster is visualized using box plots, helping us understand the characteristics of each segment.

- **Interactive Visualizations:** Using Plotly, we create interactive scatter plots to visualize the customer groupings based on annual income and spending score, making it easier to explore and analyze the clusters.
  
- **Final Clustering Model:** Based on the insights gained from the Elbow point and Silhouette analysis, we train the KMeans clustering model with the optimal number of clusters.
  
- **Cluster Characteristics and Centroids:** We identify the average values of annual income and spending score for each cluster and visualize the clusters and their centroids on a scatter plot.

# Data Exploration

The data used in this project was obtained from a mall customer survey. The survey data included the following variables:

- Annual income
- Spending score
- Gender
- Age
- Marital status
- Occupation

The data was explored using visualizations such as the elbow point graph, silhouette analysis, and box plots. These visualizations showed that the data was well-suited for clustering.

# Modeling
The KMeans clustering algorithm was used to identify customer segments. The KMeans algorithm is a simple but effective clustering algorithm that works by grouping data points together based on their similarity.

The KMeans algorithm was used to cluster the data into 5 clusters. The clustering results were evaluated using the silhouette coefficient. The silhouette coefficient is a measure of how well each data point is assigned to its cluster. The higher the silhouette coefficient, the better the clustering.

# Evaluation
The clustering results were evaluated using the silhouette coefficient. The silhouette coefficient for the 5 clusters was 0.67, which indicates that the clustering was good.

The implications of the clustering results for the mall were discussed. The mall can use the clustering results to improve its marketing strategies and customer experience. For example, the mall can target high-income customers with luxury brands, while targeting low-income customers with discount brands. The mall can also create targeted marketing campaigns for each customer segment.

# Conclusion
The results of this project show that the KMeans clustering algorithm can be used to identify distinct customer segments based on their annual income and spending score. This information can be used by the mall to improve its marketing strategies and customer experience.

# Next Steps
The next steps in this project would be to collect more data and to explore other clustering algorithms. The mall can also use the clustering results to create targeted marketing campaigns for each customer segment.

# Contact

- Kiavash D
- Email: kiavashdav@hotmail.com
- LinkedIn: https://www.linkedin.com/in/kiavash-davoodi/
