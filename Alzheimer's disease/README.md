# 🧠 Alzheimer's Disease Analysis and Prediction

This repository contains two complementary studies aimed at understanding and predicting Alzheimer’s Disease (AD) through statistical analysis and machine learning techniques. By leveraging clinical, demographic, and biomarker data, these projects provide insights into risk factors and predictive modeling for AD.

---

## 📁 Project Structure
```
Alzheimer's Disease Analysis/
│── README.md
│── alzheimers_disease_analysis.ipynb
│── alzheimer_prediction.ipynb
│── Alzheimers Disease Prediction Writeup.pdf
│── datasets/
    └── alzheimers_disease_data.csv
```

---

## Part 1: Cholesterol Levels and Alzheimer's Disease — A Data-Driven Approach

###  Objective

This section investigates the possible association between cholesterol levels and Alzheimer's Disease. While literature presents conflicting findings, this data-driven analysis provides statistical evidence using real-world clinical data.

### 🗂️ Overview

- Dataset: 2,149 patients across diverse demographics
- Goal: Determine if there's a statistically significant relationship between cholesterol levels and AD diagnosis

###  Methodology

- **Exploratory Data Analysis (EDA)**: Visualized distributions, outliers, and relationships
- **Statistical Testing**:
  - **t-tests**: Compared cholesterol levels between AD and non-AD groups
  - **ANOVA**: Assessed differences across multiple diagnosis stages
- **Regression Analysis**: Modeled the relationship between cholesterol levels and AD status

### Key Findings

- Initial analysis revealed potential associations between cholesterol levels and AD presence
- t-test and ANOVA results offered statistical insight into group differences
- Regression indicated trends worth further exploration, though causality cannot be confirmed

---

##  Part 2: Alzheimer’s Disease Detection and Prediction Using Machine Learning

###  Objective

This section focuses on building models to detect and predict Alzheimer's Disease based on patient features including cognitive scores, cholesterol, demographics, and more.

### 🗂️ Overview

- Goal: Predict AD diagnosis using supervised learning techniques
- Target variable: AD diagnosis (binary or multi-class depending on dataset granularity)

### Techniques Used

- **EDA**: Investigated key variables (MMSE, CDR, cholesterol, age, etc.)
- **Feature Engineering**:
  - One-hot encoding for categorical variables
  - Scaling and normalization
  - Dimensionality reduction (e.g., PCA)
- **Models Explored**:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
  - Neural Networks

### Evaluation

- Performance metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
- Model tuning using cross-validation and GridSearchCV
- Compared models for both interpretability and predictive power

### 📌 Key Insights

- Models showed promising results in predicting AD from clinical features
- Feature importance analysis revealed key contributors to prediction
- Neural networks and random forests yielded the best performance

---

## 🛠️ Tools & Technologies

- **Python 3.9+**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Visualization
- **SciPy, Statsmodels** – Statistical testing
- **Scikit-learn, TensorFlow/Keras** – Machine learning modeling
- **Jupyter Notebook** – Development environment

