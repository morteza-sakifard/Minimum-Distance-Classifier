# Minimum Distance Classifier
The minimum distance classifier is used to classify unknown data to classes which minimize the distance between the data and the class in multi-feature space. The distance is defined as an index of similarity so that the minimum distance is identical to the maximum similarity. The following distances are often used in this procedure.

## Euclidean Distance
The Euclidean distance between two points in Euclidean space is the length of a line segment between the two points.
![image](https://user-images.githubusercontent.com/23229539/152847389-eb4e8306-0dc0-4bf1-9757-8f4bd41f8db4.png)

Minimum Euclidean distance classifier will give better results if the following conditions are met on the dataset:
- The prior probability of all classes being equal.
- Class data is distributed normally.
- The covariance matrix of all classes is equal.  ![image](https://user-images.githubusercontent.com/23229539/152849385-bc5ac5d7-bdb0-42a5-930b-84f8b4c0a430.png)
- The covariance matrix is defined as follows.  ![image](https://user-images.githubusercontent.com/23229539/152849556-1e77dc41-8afa-4e31-ac9a-d1ed05b043ae.png)

![image](https://user-images.githubusercontent.com/23229539/152850143-cb971ad7-c08c-4365-a9b5-809561768b8f.png)

## Mahalanobis Distance
Mahalanobis distance is an effective multivariate distance metric that measures the distance between a point (vector) and a distribution.

![image](https://user-images.githubusercontent.com/23229539/152848357-908ace88-b20a-4c36-8210-e18bb5e08c63.png)
 - D^2        is the square of the Mahalanobis distance. 
 - x          is the vector of the observation (row in a dataset), 
 - m          is the vector of mean values of independent variables (mean of each column), 
 - C^(-1)     is the inverse covariance matrix of independent variables.

Minimum Mahalanobis distance classifier will give better results if the following conditions are met on the dataset:
- The prior probability of all classes being equal.
- Class data is distributed normally.
- The covariance matrix of all classes is equal.  ![image](https://user-images.githubusercontent.com/23229539/152849385-bc5ac5d7-bdb0-42a5-930b-84f8b4c0a430.png)

![image](https://user-images.githubusercontent.com/23229539/152851276-6116a32e-800c-4ddf-9e53-5beca7407380.png)


![image](https://user-images.githubusercontent.com/23229539/152848539-ffd42bf2-1e02-43f0-b21a-ecd0e2b49955.png)
