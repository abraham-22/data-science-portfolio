## Insurance Claim Risk Modeling: Detecting Anomalies in Healthcare Billing

###  Project Overview

This project aims to build a **risk-scoring model** to identify **high-risk, anomalous, or potentially fraudulent healthcare insurance claims** using patient and billing data. Fraud and abuse in healthcare billing can lead to massive financial losses and misallocation of resources. This two-stage modeling pipeline combines unsupervised anomaly detection and supervised classification to surface suspicious claims effectively.



### Objectives

-  **Detect anomalous insurance claims** using unsupervised learning techniques  
- **Assign risk scores and labels** for supervised classification  
-  **Build predictive models** to classify and flag high-risk claims for review  
-  **Support fraud prevention** efforts in healthcare systems through data-driven insights



### Tools & Technologies

- **Python 3.9+**
- **Pandas, NumPy** – Data preprocessing and manipulation  
- **Scikit-learn** – Modeling and evaluation (Logistic Regression, Random Forest, LOF, Isolation Forest, KMeans, DBSCAN)  
- **TensorFlow / Keras** – Autoencoder modeling  
- **Matplotlib, Seaborn** – Data visualization  
- **Jupyter Notebook** – Development and interactive analysis



### 🗂️ Project Structure

```
insurance-claim-risk-modeling/
│
├── dataset/ #  healthcare claim data
├── Notebook/ insurance_claim)mod.ipynb 
├── README.md # Project documentation (this file)

```


### 🔬 Methodology

#### Phase 1: Anomaly Detection (Unsupervised Learning)

- **Isolation Forest** – Detects anomalies based on how isolated a data point is in feature space  
- **Local Outlier Factor (LOF)** – Evaluates local density deviations to flag anomalies  
- **KMeans Clustering & DBSCAN** – Used to find unusual groupings and outliers  
- **Autoencoders** – Neural network-based anomaly detector using reconstruction error

> Claims with high anomaly scores across multiple models were labeled as potentially high-risk.


#### Phase 2: Risk Classification (Supervised Learning)

- Labeled data from Phase 1 used to train classifiers:
  - **Logistic Regression** – Interpretable baseline model
  - **Random Forest** – Robust ensemble model for handling feature interactions and non-linearities

- Evaluation metrics:
  - **Precision, Recall, F1-score**
  - **Confusion Matrix and ROC-AUC**


###  Key Insights

- Combining multiple anomaly detection methods increases detection reliability  
- Autoencoder and Isolation Forest produced the most consistent high-risk predictions  
- Random Forest classifier showed strong performance in classifying anomalous claims  
- This two-tiered approach enables scalable, data-driven fraud detection in healthcare billing



### Use Case Relevance

- 🧾 **Insurance Providers**: Flag suspicious claims for manual review  
- 🏥 **Healthcare Auditors**: Prioritize investigations and reduce fraud losses  
- 📉 **Cost Optimization**: Prevent overpayments and ensure claim integrity


