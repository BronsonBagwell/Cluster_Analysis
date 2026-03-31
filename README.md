# Cluster Analysis
Unsupervised learning on the Wine dataset using K-Means and Hierarchical clustering.

## Overview
This project applies unsupervised clustering techniques to the Wine dataset to discover natural groupings among wine samples. Multiple methods and validation metrics are used to determine the optimal number of clusters and compare clustering approaches.

## Dataset
- **Source:** Wine dataset (UCI Machine Learning Repository)
- **Key variables:** Chemical properties including alcohol, malic acid, ash, alkalinity, magnesium, phenols, flavanoids, and others

## Methods
- K-Means clustering with k = 2, 3, and 4 clusters
- Hierarchical clustering with complete, average, and single linkage
- Elbow method and silhouette analysis for optimal cluster selection
- NbClust package for comprehensive cluster validation across multiple indices

## Key Findings
- Three clusters provided the best separation, consistent with the three known wine cultivars
- K-Means and hierarchical clustering (complete linkage) produced similar groupings
- Single linkage performed poorly due to chaining effects in the data

## Tools & Libraries
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=R&logoColor=white)
![cluster](https://img.shields.io/badge/cluster-276DC3?style=flat-square&logo=r&logoColor=white)
![factoextra](https://img.shields.io/badge/factoextra-276DC3?style=flat-square&logo=r&logoColor=white)
![NbClust](https://img.shields.io/badge/NbClust-276DC3?style=flat-square&logo=r&logoColor=white)

## How to Run
1. Clone the repository: `git clone https://github.com/BronsonBagwell/Cluster_Analysis.git`
2. Open the HTML file in a browser, or run the R Markdown file in RStudio
3. Required packages: `cluster`, `factoextra`, `NbClust`
