# 🚗 Cluster Analysis for GHG Emission Profiles of Vehicles

## 📘 Project Overview

This project applies unsupervised machine learning techniques to analyze and group vehicles based on their greenhouse gas (GHG) emission profiles. As emissions regulations and sustainability goals become more critical, understanding vehicle emission patterns is vital for decision-makers across sectors.



## Objectives

- 📊 **Categorize vehicles** based on GHG emissions using clustering techniques  
- ⚙️ **Compare clustering algorithms**, including K-Means, Hierarchical Clustering, DBSCAN, and Gaussian Mixture Models (GMM)  
- 📈 **Evaluate clustering performance** using metrics like Silhouette Score and Davies-Bouldin Index (DBI)  
- 💡 **Provide actionable insights** for policymakers, manufacturers, and consumers



##  Tools & Technologies

- **Python 3.9+**
- **Pandas, NumPy** – Data handling and transformation
- **Matplotlib, Seaborn, Plotly** – Data visualization
- **Scikit-learn** – Clustering models and evaluation metrics
- **Jupyter Notebook** – Interactive development and analysis



## 🗂️ Project Structure
```
ghg-vehicle-clustering/
│
├── dataset/ # Contains GHG emission data
├── ghg_clustering_analysis.ipynb # Main notebook for data analysis and clustering
├── README.md # Project documentation (this file)
```



## 🔍 Methodology

### 1. **Data Preprocessing**
- Removed null and duplicate values  
- Normalized numerical features using standard scaling  
- Conducted feature selection and PCA for dimensionality reduction

### 2. **Exploratory Data Analysis (EDA)**
- Visualized emission trends across different vehicle categories  
- Analyzed correlations between engine size, fuel type, and GHG output

### 3. **Clustering Algorithms**
- **K-Means** – Baseline clustering method with k optimization using the elbow method  
- **Hierarchical Clustering** – Explored dendrograms to identify natural groupings  
- **DBSCAN** – Detected noise points and non-linear clusters  
- **Gaussian Mixture Models (GMM)** – Modeled soft probabilistic cluster assignments

### 4. **Evaluation Metrics**
- **Silhouette Score** – Measured cluster cohesion and separation  
- **Davies-Bouldin Index (DBI)** – Lower DBI indicated better-defined clusters  
- **Cluster Visualization** – Plotted 2D PCA projections for interpretability



## Key Insights

- **GMM** provided flexible, soft clustering with better separation for overlapping classes  
- **K-Means** and **GMM** performed best with optimized cluster counts (based on Silhouette and DBI scores)  
- DBSCAN helped identify outliers (extreme polluters or uncommon vehicle types)  
- **Lower DBI scores** were observed for GMM and K-Means compared to Hierarchical Clustering



## 📊 Use Case Impact

- **Policymakers** can define more precise emissions standards  
- **Manufacturers** can segment product lines based on emission efficiency  
- **Consumers** can choose vehicle categories aligned with environmental goals


