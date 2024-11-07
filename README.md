**PCA Implementation on Breast Cancer Dataset**


This project demonstrates how to apply Principal Component Analysis (PCA) to the Breast Cancer Wisconsin (Diagnostic) dataset using Python. PCA is used here to reduce the dataset's dimensionality while retaining most of the variance, making the data easier to visualize and analyze.

**Table of Contents:-**

Overview of PCA

Dataset Information

Project Setup

Code Overview

Requirements

Usage

**Overview of PCA:-**

Principal Component Analysis (PCA) is a widely used technique in machine learning and statistics for dimensionality reduction. It works by transforming data into a new coordinate system where the greatest variances are represented along the first coordinates, known as principal components. This transformation helps in:

Reducing the number of dimensions while keeping most of the important information (variance) intact.
Simplifying the dataset for visualization and analysis.
PCA is often applied to datasets with a large number of features to make data visualization easier and to reduce computational costs in machine learning.

**Dataset Information:-**

We use the Breast Cancer Wisconsin (Diagnostic) dataset from the sklearn.datasets library. This dataset includes data about cell nuclei features computed from digitized images, used to classify cancerous tumors as malignant or benign.

Number of Instances: 569
Number of Attributes: 30 numeric features
Classes: Malignant, Benign

**Project Setup:-**

Clone this repository.
Install the required dependencies using the following command:
bash
Copy code
pip install -r requirements.txt

**Code Overview:-**

The code performs the following steps:

Load and Explore the Dataset: Uses the load_breast_cancer function from sklearn.datasets to load the dataset and display its structure.
Data Standardization: Applies standardization to the dataset to ensure that each feature has a mean of 0 and a standard deviation of 1, which is essential for PCA.
PCA Transformation: Reduces the data to 2 principal components for easy visualization.
Visualization: Uses a scatter plot to visualize the data points, with colors representing different classes (malignant or benign).
Requirements
Python 3.x
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
