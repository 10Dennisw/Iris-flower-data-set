# The Dataset
- The Iris dataset is a well-known set of data used for pattern recognition and machine learning education. It was introduced by the British statistician and biologist Ronald Fisher in 1936 in his paper "The Use of Multiple Measurements in Taxonomic Problems"
- The dataset consists of 150 samples from three different species of iris flowers: Iris setosa, Iris versicolor, and Iris virginica. Each species has 50 samples.
- There are four features measured for each sample:
  - Sepal length 
  - Sepal width
  - Petal length
  - Petal width
# t-Distributed Stochastic Neighbour Embedding (t-SNE)
- t-SNE is  used for dimensionality reduction and visualizing high-dimensional data in a low-dimensional space
- t-SNE is preserves the local structure of high-dimensional data and revealing clusters or patterns in the data.
- In this case, t-SNE allows use to see the clusters of the three classes in the Iris dataset.
# Support Vector Machines (SVMs)
The goal often of this repository is to classify the iris flowers into one of the three species based on the measurements of their petals and sepals.
To achieve the classification task SVMs are used.
1. SVMs work in a feature representation space, where each data is represented by a vector of it’s features.
2. SVMs find the best possible hyper plane which separates the data points of different classes
    - The hyperplane is a flat affine subspace that divides the space into two parts
    - SVM finds the ‘best’ hyperplane that has a maximum margin.
    - The margin is the distance between the hyperplane and the nearest data point from each class.
    - The idea is that maximising the margin helps to build a model that is better generalised and thus less sensitive to overfitting 
