Correlation Clustering
======================

Correlation clustering techniques provide the ability to cluster similar data into groups. Unlike other
clustering algorithms, such as k-means, correlation clustering does not require an initial guess for the
number of clusters. Instead, it takes as input a similarity matrix, which provides a similarity measure
between each pair of data points. The algorithm produces the optimal clustering based on the similarity
matrix. The correlation clustering problem is known to be NP-hard.

The included Jupyter notebook compares various implementations of correlation clustering. Specifically,
Integer Linear Programming (ILP) implementations will be compared against weighted Max-SAT formulations.