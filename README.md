# Aprendizaje No Supervisado/ Unsupervised Learning
This project focuses on unsupervised learning to segment mall customers using the `K-Means clustering algorithm`. The primary goal is to identify distinct customer groups based on features like age, annual income, and spending score, providing valuable insights for targeted marketing strategies.

The analysis involves several key steps:

## Methodology
- **Data Exploration**: Understanding the characteristics of the customer data.
- **Data Preprocessing**: This includes standardization (using `sklearn.preprocessing`) to ensure that all features contribute equally to the clustering process.
- **Cluster Analysis**:
    - The K-Means clustering model from the `sklearn.cluster` library is used to group customers.
    - The optimal number of clusters is determined using both the Silhouette score and the Elbow method.
- **Dimensionality Reduction**: Principal Component Analysis (PCA) from `sklearn.decomposition` is applied to reduce the dimensionality of the data, primarily for enhanced visualization of the clusters.
- **Visualization**: Libraries such as `matplotlib.pyplot` and `seaborn` are utilized to visualize the clusters and explore the distribution of gender across them.
## Business Impact
In business terms, this project directly assists a mall's marketing team in gaining a deeper understanding of their customer base. By identifying different customer segments, the team can develop personalized marketing campaigns tailored to the specific needs and preferences of each group. This targeted approach has the potential to increase sales and significantly improve customer satisfaction.




Sequence diagram of the data pipeline and model training process:

<img width="1043" alt="data pipeline and model training process for Unsupervised Learning" src="https://github.com/user-attachments/assets/2667e2f1-9533-4c82-b43d-25314b62710c" />
