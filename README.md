# Principal Component Analysis and Visualization

## Introduction to Principal Component Analysis(PCA)
Principal Component Analysis (PCA) is a statistical technique used to simplify complex datasets. Imagine you have a dataset with many variables, and these variables are possibly correlated (e.g., height and weight of individuals). PCA helps to reduce the number of variables while retaining the essential information.

## Procedure of PCA
* Load the IRIS data
* Check correlation with visualization
* Prepare the X dataframe by identifying binary columns, 
* Feature normalization
* Apply PCA and capture the amount of variance each principal component explain
* Visualize the cumulative explained variance ratio with line and scatter plot
* Visualize the Kmeans clustering result to see how different clusters spread out across the first and second principal components with the Elbow Curve
* Draw a Pair-wise Scatter plot to visualize how different y_iris spread out across each pair of principal components
* Draw a 3D plot to show the total explained variance


## Result
By visualizing the PCA result, it helps select the number of PCA components to best reduce the number of variables without losing significant informative data.
