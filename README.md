Principal Component Analysis

This project implements  PCA from the group and covers all the mathematical foundation and provides practical insights into dimensionality reduction techniques.

Source: https://www.kaggle.com/datasets/adilshamim8/student-performance-and-learning-style
Data collected by a student from African Leadership University
Author: Michael Kimani
Github: Mikekimm

Tasks done:
Building the PCA from scratch
I built the covariance matrix manually
Perform eigendecomposition
I projected the data into principal component space
Implemented Inverse transformation

The Dynamic Component Section
I automatically selected the number of components based on variance thresholds
I analyzed trade-off between dimensionality and data retention
I visualized how variance changes as i added components

Performing Optimization
I implemented PCA using Singular Value Decomposition for numerical stability.
I used a batch processing to make it memory efficient

Key Findings I Found out
The first 5 comments explain 38.81% of the variance
The first principal component captures 12.35% of the variance
This approach reduced data dimensionality significantly

Tech I Used:
Python
Numpy
Pandas
Matplotib and Seaborn
Jupyter Notebook

To try it yourself
gitclone https://github.com/Mikekimm/Principal-Component-Analysis.git
cd Principal-Components-Analysis
Pip install numpy pandas matplotlib seaborn scikit- learn
jupyter  notebook PCA_Assignment.ipynb


This data was collected by a student from African Leadership University
I focused on academic performance and study habits of African students
14,003 rows x 16 features. It serves as a solid introduction to dimensionality reduction and gives insights into how real-world educational data can be analyzed to extract meaningful patterns.
