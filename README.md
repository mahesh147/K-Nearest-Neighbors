# K-Nearest-Neighbors

A simple implementation of K Nearest Neighbors classifier model in python. The classifier object is created using the KNeighborClassifier class which was imported from sklearn.neighbors.

The parameters passed into the KNeighborsClassifier include:
 - n_neighbors = 5. This is the default value of the n_neighbors argument. Increasing the value of n_neighbors increases the value of K. For example, if n_neighbors is given a value of 5, the number of neighbors taken for comparing the value of the new data point will be 5.

 - metric = 'minkowski'. This metric uses Euclidean metric.

 - p = 2. This is the power parameter. The value 2 is given for Eculidean distance.

A confusion martrix is later created to determine the accuracy of the model. 
