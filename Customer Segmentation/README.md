# 📊 Comparing Clustering Algorithms for Customer Segmentation

##  Project Overview

This project focuses on comparing multiple clustering algorithms to effectively segment customers based on **RFM (Recency, Frequency, Monetary)** analysis. By evaluating cluster quality and business outcomes like **Customer Lifetime Value (CLV)** and **churn prediction**, the project aims to uncover the most impactful segmentation strategy for customer relationship management.



## Objectives

- 🧠 **Compare clustering techniques** (K-Means, Hierarchical, DBSCAN, GMM) for customer segmentation  
- 🔍 **Evaluate cluster quality** using metrics such as Silhouette Score and Davies-Bouldin Index (DBI)  
- 💰 **Analyze the impact** of clustering on downstream business metrics like CLV and churn prediction  



## Tools & Technologies

- **Python 3.9+**
- **Pandas, NumPy** – Data wrangling and feature creation  
- **Matplotlib, Seaborn, Plotly** – Data visualization  
- **Scikit-learn** – Clustering models, evaluation metrics  
- **XGBoost / RandomForest** – Optional: Predictive models for CLV and churn  
- **Jupyter Notebook** – Interactive development and analysis environment  



## 🗂️ Project Structure

```
customer-segmentation-clustering/
│
├── dataset/ # customer transaction data
├── customer_segmentation.ipynb # Notebook with clustering and evaluation
├── README.md # Project overview (this file)

```



## 🔍 Methodology

### 1. **Feature Engineering with RFM**
- **Recency**: Days since last purchase  
- **Frequency**: Number of purchases  
- **Monetary**: Total spend  

### 2. **Clustering Techniques Compared**
- **K-Means** – Efficient baseline model  
- **Hierarchical Clustering** – Dendrogram-based segmentation  
- **DBSCAN** – Captures noise and arbitrary-shaped clusters  
- **Gaussian Mixture Models (GMM)** – Soft clustering using probabilistic distribution

### 3. **Cluster Evaluation Metrics**
- **Silhouette Score** – Measures cohesion and separation  
- **Davies-Bouldin Index (DBI)** – Lower values indicate better clustering  
- **Elbow Method** – Used to determine optimal number of clusters  

### 4. **Business Impact Analysis**
- Analyzed **Customer Lifetime Value (CLV)** distribution across clusters  
- Assessed **churn risk** per segment to inform retention strategies  
- Linked clustering insights to actionable marketing recommendations



## Key Insights

- GMM and K-Means yielded the most interpretable and well-separated clusters  
- High-value customer segments were identified with significantly higher CLV and lower churn risk  
- Clustering provided a strong foundation for **targeted marketing** and **customer retention** strategies  



## Applications

- 📢 **Marketing**: Personalize campaigns based on segment profiles  
- 📉 **Churn Reduction**: Flag high-risk segments for proactive engagement  
- 💹 **Revenue Growth**: Target high CLV clusters with loyalty initiatives  

