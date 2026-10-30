Name: Pranshu Ranjan
Registration Number: 23BDS0249
Course: Exploratory Data Analysis (EDA)

using Python on Google Colab

**_Project Overview_
**

This repository contains the implementation of Exploratory Data Analysis and various statistical and machine learning techniques using Python.

The analysis is performed on the PhD Publications dataset, which contains information about researchers, their publication records, academic prestige, gender, marital status, number of children, and mentor publications.

The objective is to understand the dataset, identify patterns and relationships, visualize distributions, and apply different machine learning algorithms.

Dataset Information

* Dataset: PhDPublications.csv
* Source: GitHub – Salem Prakash
* Records: 915
* Attributes: 7

Dataset Attributes

Attribute	Description
rownames	Record identifier
articles	Number of articles published
gender	Gender of researcher
married	Marital status
kids	Number of children
prestige	Academic prestige score
mentor	Number of publications by mentor

Experiments and Implementation

Phase 1: Data Loading and Understanding

* Importing required Python libraries.
* Loading the dataset using Pandas.
* Examining dataset dimensions and structure.
* Displaying descriptive statistics.

Phase 2: Data Preprocessing

* Identifying and handling missing values.
* Removing duplicate records.
* Cleaning and standardizing column names.

Phase 3: Data Normalization

* Applying Min-Max Scaling.
* Transforming numerical attributes into a common range.

Phase 4: One-Dimensional Statistical Analysis

* Mean, Median and Mode.
* Variance and Standard Deviation.
* Skewness and Kurtosis.
* Frequency Distribution.

Phase 5: One-Dimensional Visualization

* Histograms.
* Boxplots.
* Density Plots.

Phase 6: Two-Dimensional Statistical Analysis

* Covariance.
* Pearson Correlation.
* Spearman Correlation.

Phase 7: Two-Dimensional Visualization

* Scatter Plots.
* Correlation Heatmaps.

Phase 8: Three-Dimensional Analysis

* Three-variable statistical analysis.
* Three-dimensional Scatter Plots.

Phase 9: K-Means Clustering

* K-Means Clustering implementation.
* Elbow Method.
* Silhouette Score.
* Cluster and Centroid Visualization.

Phase 10: Hierarchical Clustering

* Agglomerative Clustering.
* Linkage Methods.
* Dendrogram Visualization.
* Cluster Visualization.

Phase 11: Clustering Comparison

* Comparing K-Means and Hierarchical Clustering.
* Evaluating clustering performance.

Phase 12: Principal Component Analysis (PCA)

* Feature Standardization.
* Dimensionality Reduction.
* Principal Component Extraction.
* Explained Variance Analysis.
* Scree Plot.
* Two-Dimensional PCA Visualization.

Phase 13: Simple Linear Regression (SLR)

* Independent and Dependent Variable Selection.
* Train-Test Split.
* Linear Regression Model Training.
* Regression Equation.
* Prediction and Model Evaluation.
* MAE, MSE, RMSE and R² Score.
* Regression and Residual Plots.

Phase 14: Classification

Implementation of three classification algorithms:

1. Logistic Regression
2. Decision Tree Classifier
3. K-Nearest Neighbors (KNN)

Evaluation techniques:

* Accuracy Score.
* Confusion Matrix.
* Precision.
* Recall.
* F1-Score.
* Model Accuracy Comparison.

Technologies and Libraries Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

Repository Structure

Pranshu_Ranjan_eda/
│
├── Pranshu_Ranjan_1.ipynb
└── README.md

Execution

1. Open the notebook using Google Colab.
2. Execute the cells sequentially.
3. The dataset is loaded directly from its GitHub source.
4. Run each experiment to view the corresponding outputs and visualizations.

Conclusion

This project demonstrates the application of Python for exploratory data analysis, statistical summarization, data visualization, clustering, dimensionality reduction, regression and classification.

It provides practical experience in understanding datasets, identifying patterns, analyzing relationships and applying machine learning techniques to real-world data.
