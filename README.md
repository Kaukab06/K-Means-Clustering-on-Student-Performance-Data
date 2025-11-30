
<h1 align="center">K-Means Clustering on Student Performance Data</h1>

<p align="center">Unsupervised Machine Learning | Data Segmentation | Visualization</p>


This project applies K-Means Clustering, an unsupervised machine learning technique, to group students based on their performance patterns. Using the WCSS (Within Cluster Sum of Squares) and Elbow Method, the optimal number of clusters is identified and visualized. The clusters are then plotted with different colors to observe how students are grouped based on similarity in their performance metrics.

The dataset contains multiple student features, and clustering helps understand patterns such as students who perform similarly, possible learning groups, and category-based segmentation.

# Workflow Summary

Load student performance dataset (student_clustering (1).csv)

Select relevant features for clustering

Apply K-Means algorithm for multiple cluster values (k = 1 to 10)

Compute WCSS for each cluster value

Plot Elbow Curve to determine optimal clusters

Train final K-Means model on chosen cluster number

Visualize resulting clusters in a scatter plot

# Concepts Used
Concept	Purpose
K-Means Clustering	Grouping students by similarity
WCSS	Cluster compactness measurement
Elbow Method	Selecting best number of clusters
Data Visualization	Understanding cluster structure

# Files Included
File Name	Description
K-Means Clustering on Student Performance Data.ipynb	Jupyter notebook with full code & outputs
student_clustering (1).csv	Student performance dataset used for clustering
README.md	Documentation for the project

# Tools & Libraries
Python
NumPy
Pandas
Matplotlib
Scikit-learn
VS Code 

# Install dependencies:
pip install numpy pandas matplotlib scikit-learn

# Insight
The final clustering visualization clearly separates student groups based on performance characteristics, which can help in:
Academic performance analysis
Identifying strong vs weak learners
Personalized study recommendations
