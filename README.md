This project was created in order to implement the K-means algorithm on images. 

The K-means algorithm takes two arguments: the number of clusters and the image transformed into color values. It initially creates a random mean for each cluster, 
and classifies each pixel according to which cluster mean is closest to it. Then, new cluster means are calculated by using all of the pixels that were attributed 
to each of the initial means. 

These cluster means are used in the next iteration of the algorithm stated previously.

The algorithm continues until all of the cluster means' values have not changed for two iterations of the algorithm.

The resulting images shown in the python notebook are the images redrawn using the final cluster means calculated in the k-means algorithm. The values of k used
for each image were 1, 2, 5, 10, and 20.

This algorithm is used to classify objects in images, such as handwritten digits.
