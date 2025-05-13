# ❤️ Regression Analysis for Predicting Heart Disease

##  Project Overview

This project focuses on using **regression analysis** to investigate and predict the likelihood of **heart disease** based on five key predisposing medical conditions. By analyzing patient health metrics, the goal is to detect patterns and quantify the relationship between these factors and the onset of heart disease.



##  Objectives

- Analyze the role of five major predisposing factors:
  - **BMI (Body Mass Index)**
  - **Hypertension**
  - **Triglycerides**
  - **Low-Density Lipoproteins (LDL)**
  - **Diabetes**
  
-  Perform regression analysis to:
  - Identify statistically significant predictors
  - Model the relationship between health conditions and heart disease
  - Detect data-driven patterns that can inform early intervention strategies


## Tools & Technologies

- **R Programming Language**
- **RStudio** – IDE used for scripting and visualization  
- **ggplot2, dplyr, stats** – For data manipulation, plotting, and regression modeling  
- **Base R** – For data import, cleaning, and exploratory data analysis (EDA)  


## 🗂️ Project Structure

```
heart-disease-regression/
│
├── dataset/ # raw health records dataset
├── Project writeup and heart_disease_analysis.R # R script with full analysis workflow
├── README.md # Project documentation (this file)

```


## 🔬 Methodology

1. **Data Preparation**
   - Imported and cleaned the dataset to handle missing values and inconsistencies  
   - Converted categorical variables where necessary for regression analysis

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions and relationships among variables  
   - Identified potential multicollinearity and outliers

3. **Regression Modeling**
   - Applied **linear and logistic regression** depending on outcome variable format  
   - Assessed feature significance using p-values and confidence intervals  
   - Evaluated model performance using **R-squared**, **AIC**, and **residual analysis**



## Key Insights

- Variables such as **hypertension**, **high triglycerides**, and **LDL levels** showed strong correlation with heart disease outcomes  
- **BMI** and **diabetes** also contributed meaningfully, though to varying degrees based on interaction effects  
- Regression models successfully identified at-risk individuals, supporting clinical decision-making and preventive care planning


##  Real-World Impact

- Helps **clinicians** prioritize risk factors during health assessments  
- Informs **public health initiatives** aimed at early detection and prevention  
- Aids in **developing personalized treatment plans** based on patient-specific data

