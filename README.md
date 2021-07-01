# Facial Recognition Project 2
The project was implemented using Matlab programming. The provided face data were raster-scanned face images (46x56 pixels) in columns.
The aim of the project is to use various metrics and data representations for facial recognition to observe their properties.

## Section 1 - Distance Metrics 
1) Data Preparation 
a) Using original unmodified images as feature vectors.
b) Normalizing feature vectors to unit norm L2.

2) kNN retrieval is performed on features, using standard non-learned distance metrics.
3) Histogram of pixel intensities are used as the feature representations and standard non-learned distance metrics are used to evaluate the performance.
4) Mahalanobis distance metric is implemented.
5) Dimensionality reduction with PCA and LDA on feature
vectors is performed.
6) Mahalanobis metric learning is performed. Results are reported with the following distance metric learning techniques: RCA
(Relevant Component Analysis), NCA (Neighborhood Components Analysis), LMNN
(Large Margin Nearest Neighbors). The resuls are compared with (4)


## Section 2 - Cluster based representations
1) Clustering.
a) k-means clustering is implemented.
b) Agglomerative clustering is implemented.
2) Clustering is performed on the test data. A method is proposes and implemented to assign label to the cluster
3) New representation of images is obtained using Fisher vectors
a) Cluster centres are used as a codebook and then vectors of distances to the cluster centres as
feature vectors.
b) Softmax probabilities of inverse distances to cluster centres are used as the vector representation.
c) Fisher vectors from GMM is obtained.
4) Results are reported for representations from 4.a, 4.b and 4.c.
