# Clustering-analysis-project-for-customer-segmentation
This report analyzes customer segmentation using K-Means (k=4, silhouette 0.35) and hierarchical clustering (0.25). Preprocessing included one-hot encoding and standardization. Clusters revealed distinct spending patterns; K-Means outperformed. Strategies: targeted marketing, regional promotions. 

This project details a customer segmentation analysis using K-Means and hierarchical clustering. Key steps include:

Data Preprocessing:

No missing values detected. Categorical variables ('Channel', 'Region') were one-hot encoded.

Numerical features standardized via StandardScaler to ensure equal weighting. A 10% subsample was used for preliminary analysis.

Clustering Implementation:

K-Means: Optimal clusters (
k
=
4
k=4) identified using the elbow method (SSE plot). Centroids revealed distinct spending patterns (e.g., Cluster 1: high 'Milk'/'Grocery').

Hierarchical Clustering: Ward linkage dendrogram confirmed 
k
=
4
k=4, aligning with K-Means.

Result Comparison:

K-Means outperformed hierarchical clustering in silhouette scores (0.35 vs. 0.25), indicating clearer cluster separation.

Strengths/Weaknesses: K-Means is efficient for spherical clusters but outlier-sensitive; hierarchical offers flexibility but is computationally intensive.

Discussion:

Unsupervised vs. Supervised: K-Means grouped intrinsic patterns, while SVM achieved 84% accuracy predicting 'Region' but struggled with class imbalance.

Business Strategies: Proposed actions include targeted marketing (e.g., bulk deals for high-spending clusters), regional promotions leveraging SVM insights, and loyalty programs tailored to cluster behaviors.

Conclusion: The project demonstrates clustering’s effectiveness in deriving actionable business insights, with K-Means providing robust segmentation. Methodological reproducibility and integration of unsupervised/supervised approaches highlight its applicability for data-driven decision-making.
