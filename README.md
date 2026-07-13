# Healthcare Business Analytics

## Overview

This project analyzes a large-scale U.S. hospital dataset to identify the operational, financial, and quality-related factors influencing hospital performance. Statistical analysis, Principal Component Analysis (PCA), clustering, and segmentation techniques were applied to uncover patterns across hospitals and generate actionable business insights.

---

## Objectives

- Analyze operational, financial, and quality performance across hospitals
- Identify key variables driving profitability and CMS Summary Star Ratings
- Reduce data dimensionality using Principal Component Analysis (PCA)
- Compare hospital performance across regions, hospital size, and urban/rural classifications
- Discover hidden patterns using clustering techniques
- Generate data-driven recommendations for healthcare performance evaluation

---

## Dataset

The analysis uses a merged hospital dataset containing financial, operational, and quality metrics, including:

- Hospital financial performance
- Net income
- Revenue and operating costs
- CMS Summary Star Ratings
- Patient satisfaction metrics
- Hospital size and capacity
- Geographic location
- Rural vs. Urban classifications

---

## Methodology

### Data Preparation

- Data cleaning
- Missing value imputation
- Feature selection
- Data standardization

### Exploratory Data Analysis (EDA)

- Distribution analysis
- Correlation analysis
- Descriptive statistics
- Feature exploration

### Principal Component Analysis (PCA)

- Component weight analysis
- Explained variance analysis
- Scree plot evaluation
- Elbow point analysis
- Dimensionality reduction

### Segmentation Analysis

- Urban vs. Rural hospitals
- Hospital bed-size categories
- Regional analysis (West, South, Midwest, Northeast)

### Machine Learning

- K-Means Clustering
- Cluster evaluation using Silhouette Score

### Visualization

- PCA projection plots
- Scree plots
- Correlation heatmaps
- Cluster visualizations
- Regional comparison charts

---

## Key Findings

- Financial variables such as operating costs, revenue, and hospital size explained the greatest variation in hospital performance.
- Patient satisfaction metrics formed a separate principal component, highlighting their independent contribution to hospital quality.
- Hospital profitability varied substantially across regions, hospital sizes, and urban/rural classifications.
- Medium-sized hospitals generally demonstrated stronger financial performance than very small or very large hospitals.
- PCA successfully reduced data complexity while preserving key information for downstream analysis and visualization.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Skills Demonstrated

- Statistical Analysis
- Principal Component Analysis (PCA)
- Exploratory Data Analysis (EDA)
- Machine Learning
- K-Means Clustering
- Data Visualization
- Feature Engineering
- Business Intelligence
- Healthcare Analytics
- Data Interpretation

---

## Repository Contents

- `Hospital_Analytics.ipynb` — Complete analytical workflow
- `images/` — Key figures and visualizations
- `README.md` — Project overview


## Business Impact

This project demonstrates how statistical analysis and machine learning can support healthcare decision-making by identifying the financial, operational, and quality factors associated with hospital performance. The findings can help healthcare organizations prioritize operational improvements, evaluate performance across hospital segments, and support evidence-based strategic planning.
