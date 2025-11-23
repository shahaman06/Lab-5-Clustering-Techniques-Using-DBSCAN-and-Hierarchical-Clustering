# Lab 5

## Purpose
The goal of this lab is to explore clustering techniques, specifically Hierarchical and DBSCAN clustering, using the Wine dataset. Clustering is evaluated using both visualizations and metrics.

## Key Insights
- Hierarchical clustering produces interpretable dendrograms and works well for smaller datasets.
- DBSCAN can detect noise and irregular cluster shapes, but results are sensitive to `eps` and `min_samples`.
- Comparing algorithms: Hierarchical provides structured clusters; DBSCAN highlights dense regions and outliers.

## Challenges
- Choosing optimal parameters for DBSCAN required experimentation.
- Visualizing clusters in high dimensions was simplified using first two features.
