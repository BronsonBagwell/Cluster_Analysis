# Cluster Analysis
Unsupervised learning on the Wine dataset using K-Means and Hierarchical clustering.

## Overview
This project applies unsupervised clustering techniques to the Wine dataset to discover natural groupings among wine samples. Multiple methods and validation metrics are used to determine the optimal number of clusters and compare clustering approaches.

## Dataset
- **Source:** Wine dataset (UCI Machine Learning Repository)
- **Key variables:** Chemical properties including alcohol, malic acid, ash, alkalinity, magnesium, phenols, flavanoids, and others

## Methods
- K-Means clustering with k = 2 and k = 3 clusters
- Hierarchical clustering with complete linkage on Euclidean distances
- Silhouette analysis for optimal cluster selection
- NbClust package for comprehensive cluster validation across multiple indices

## Key Findings
- Three clusters provided the best separation, consistent with the three known wine cultivars
- K-Means matched the known cultivar labels for 96.63% of wines (Kappa 0.949), while hierarchical clustering (complete linkage) matched 83.71% (Kappa 0.755)

## Tools & Libraries
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=R&logoColor=white)
![caret](https://img.shields.io/badge/caret-276DC3?style=flat-square&logo=r&logoColor=white)
![cluster](https://img.shields.io/badge/cluster-276DC3?style=flat-square&logo=r&logoColor=white)
![factoextra](https://img.shields.io/badge/factoextra-276DC3?style=flat-square&logo=r&logoColor=white)
![NbClust](https://img.shields.io/badge/NbClust-276DC3?style=flat-square&logo=r&logoColor=white)

## How to Run
1. Clone the repository: `git clone https://github.com/BronsonBagwell/Cluster_Analysis.git`
2. Open the HTML file in a browser, or run the R Markdown file in RStudio
3. Required packages: `caret`, `cluster`, `factoextra`, `NbClust`
