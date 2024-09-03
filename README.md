Feature Selection and Dimensionality Reduction Tasks
Overview
This repository contains tasks related to feature selection and dimensionality reduction, which are critical steps in preparing data for machine learning models. The tasks utilize the NSL-KDD dataset, which is commonly used in cybersecurity research to classify network traffic and detect various types of cyber attacks.

Structure
The repository includes the following components:

Python Notebook Files: This folder contains all the Jupyter notebooks used for the tasks.

Task 1: Feature Selection:

Focuses on selecting the most relevant features from the dataset.
Includes the implementation of techniques such as Variance Thresholding and SelectKBest with f_classif for univariate feature selection.
The goal is to reduce the number of features while maintaining model accuracy.
Task 2: Dimensionality Reduction:

Explores methods to reduce the dimensionality of the dataset.
Principal Component Analysis (PCA) is used to project the features into a lower-dimensional space, while retaining as much variance as possible.
This task also compares the performance of models trained with reduced features to those trained with the full set.

Run the Notebooks:

Open the Jupyter notebooks in the Python Notebook Files folder to run the tasks.
Ensure all necessary libraries such as pandas, numpy, scikit-learn, and matplotlib are installed.
Understand the Tasks:

Review the notebooks for Task 1 and Task 2 to understand the feature selection and dimensionality reduction techniques applied.
Task 3 offers additional insights through data visualization.
Dependencies
Python 3.x
Jupyter Notebook
pandas
numpy
scikit-learn
matplotlib
