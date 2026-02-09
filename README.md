Income Data Clustering using K-Means with Min-Max Scaling
Project Overview

This project performs unsupervised clustering on the income_full dataset using the K-Means algorithm. Feature scaling with Min-Max normalization and cluster selection using the Within-Cluster Sum of Squares (WCSS) elbow method are applied to obtain meaningful cluster separation.

Problem Statement

The objective is to segment income data into distinct groups based on numerical income-related features without predefined labels, enabling better understanding of income distribution patterns.

Dataset

The project uses the income_full dataset containing numerical attributes associated with income.
These features are scaled and used for clustering analysis.

Methodology

Loaded and explored the dataset

Applied Min-Max scaling for feature normalization

Calculated WCSS values to determine the optimal number of clusters

Implemented the K-Means clustering algorithm

Visualized clustered income groups for interpretation

Machine Learning Technique

K-Means clustering (unsupervised learning) with Min-Max feature scaling and WCSS-based cluster selection.

Results

The clustering process successfully grouped the income data into meaningful segments, demonstrating clear separation after normalization and optimal cluster selection.
