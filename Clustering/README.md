# Clustering Project

This project aims to demonstrate the understanding and application of clustering techniques for grouping and segmentation. We will use the "McDonaldsMenu.csv" dataset to perform clustering analysis and draw insights related to the provided questions.

## Project Overview

The main objective of this project is to apply clustering techniques to the "McDonaldsMenu.csv" dataset. The dataset contains information about McDonald's menu items, including attributes such as calories, carbohydrates, fat, and protein. By performing clustering analysis, we will group similar menu items together and gain insights into their unique features.

### Dataset Description

The "McDonaldsMenu.csv" dataset is provided as the input for this project. It includes various attributes related to McDonald's menu items, such as calories, carbohydrates, fat, protein, and others. We will utilize this dataset to perform clustering analysis and draw insights related to the provided questions.

### Project Tasks

The project can be divided into the following tasks:

1. Data cleaning:
   - Remove the "Category" and "Item" columns for clustering purposes.
   - Drop the "Serving Size" column or clean the values to obtain values in ounces (oz) or grams (g) and remove the units.

2. Data scaling (normalization):
   - Scale the data before clustering to ensure all variables are on the same scale.

3. Finding optimal number of clusters:
   - Generate the Within-Cluster Sum of Squares (WSS) plot (Knee plot) to find the optimal number of clusters.
   - Plot the Silhouette Coefficient to support the answer.

4. K-Means clustering:
   - Perform K-Means clustering again with the optimal number of clusters determined from the WSS plot.

5. Visualization of clustering results:
   - Visualize the clustering results using appropriate visualization techniques, such as scatter plots or parallel coordinates plots.

6. Cluster-specific data frames:
   - Use the cluster labels obtained from K-Means clustering to create cluster-specific data frames.

7. Insights from clustering results:
   - Generate at least three insights from the clustering results to show unique and interesting features for each cluster.
   - Discuss your findings and provide explanations for the characteristics of each cluster.

8. Naming the clusters:
   - Suggest unique names for each cluster based on their characteristics.
   - For example, if a cluster shows a high sugar level, it can be named the "Sugar Lovers" cluster.
