# Dimension-reduction-and-clustering


## I: Project Overview 
The objective of the project is to predict house sale price. Two methods are explored to achieve prediction- Dimension reduction and Clustering. 

In dimension reduction, we apply PCA on the numerical features and MCA on the categorical features. We will tune PCA and MCA using a train/valid and test split. Finally, we will tune parameters & perform ridge regression on the reduced features and find the mean squared error.For dimension reduction, we will compare the results by performing ridge regression on the original dataset.

In clustering, we will use Gower distance on the mixed numerical and categorical dataset. The Gower distance is essentially a special distance metric that measures numerical data and categorical data separately, then combine them to form a distance calculation. We will apply k-mediods clustering method and obtain the clusters. For clustering, we will compare the result with the ground truth.

## II: Introduction 
In this notebook, we will be applying dimension reduction techniques and a clustering method on the housing dataset. The housing dataset can be found here (https://drive.google.com/file/d/1F9Z03GYHppfBbmDFvNsA89i2OQm8N-4T/view?usp=sharing). The response variable on this dataset is the price of the house. The dataset contains 80 features (including the response variable) and 1460 observations. After removing columns with more than 30 null values, we are left with 64 features (including response). Out of the 63 predictor variables, 34 variables are numerical and 29 variables are categorical.
