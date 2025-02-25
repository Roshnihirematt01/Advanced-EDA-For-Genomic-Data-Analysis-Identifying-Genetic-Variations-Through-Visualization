# Advanced-EDA-For-Genomic-Data-Analysis-Identifying-Genetic-Variations-Through-Visualization
This project performs exploratory data analysis (EDA) and statistical computations on a genomic dataset. The goal is to identify genetic variations through visualization techniques.

Key Features
Data Loading & Preprocessing:

Reads the dataset using pandas.

Handles missing values by either filling with the mean or dropping rows.

Encodes categorical data using OneHotEncoder.

Dimensionality Reduction:

Standardizes numerical features using StandardScaler.

Applies Principal Component Analysis (PCA) for feature reduction and visualization.

Uses t-SNE for non-linear dimensionality reduction.

Statistical Analysis:

t-Test: Compares two groups if applicable.

ANOVA: Tests for differences across multiple groups.

Chi-square Test: Analyzes categorical feature associations.

Visualization:

Generates scatter plots for PCA and t-SNE projections to visualize data structure.
