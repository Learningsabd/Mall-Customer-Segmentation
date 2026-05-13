#  Mall Customer Segmentation

This project applies unsupervised machine learning techniques to segment mall customers based on demographic and spending behavior. The goal is to identify actionable customer groups for targeted marketing and business strategy.

---

* Dataset
Features used:
  - Age
  - Annual Income(k$)
  - Spending Score(1-100)
Source : Mall Customer dataset from Kaggle

---

* Methods
Three clustering algorithms were applied and compared:
  - K-Means Clustering
  - Agglomerative Clustering (Type of Hierarchical Clustering)
  - DBSCAN (Density-Based Clustering)

---

##  Objectives
- Perform exploratory data analysis (EDA)
- Apply and compare different types of clustering techniques to segment customers
- Visualize clusters and interpret business relevance
- Label clusters based on age and spending patterns

---

##  Key Features
- Correlation analysis for feature selection
- Elbow method and silhouette score for optimal cluster count
- Cluster labeling strategy based on feature distributions

---

* Evaluation Results
Method         |   Silhouette Score   |           Interpretation
-------------------------------------------------------------------------------
K-Means        |       0.426          |   Best Separation and cohesion overall
Agglomerative  |       0.420          |   Very close to K-Means but slightly leass tight
DBSCAN         |       0.310          |   Weak structure, struggled with density-based clusters

---


* Visualizations
  - Correlation Heatmap (Age, Income, Spending Score)
  - Silhouette Score plots for K-Means, Agglomerative, DBSCAN
  - Cluster profile bar plots

---

*Conclusion
  - K-Means(k=6) provided the best clustering quality
  - Clusters were labeled based on Age and Spending Score, yielding actinaable business insights.
  - This segmentation can guide marketing strategies:
    >  Target young high spenders with premium offers.
    > Retain moderate spenders with loyalty preograms.
    > Offer discount to low spenders.

---

##  Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn for clustering 
- Jupyter Notebook for analysis
- GitHub for version control and documentation

---
