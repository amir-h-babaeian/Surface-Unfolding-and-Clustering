##Source code for papers titled:
**Constrained Shortest-Path Distances with Applications to Surface Unfolding and Clustering**
+ Ery Arias-Castro 
+ Amir Babaeian
+ Thibaut Le Gouic

```
 Amir Babaeian
 Email: ababaeian@ucsd.edu
```

Thanks to Professor Ery Arias-Castro for his advises during the project.

##How to use the code:

In order to use the code you should run the demo file as follow:

Example:
```matlab
% labels = Path_Based_Clustering( data, k, no_landmarks,angle_constraint,no_clusters );
labels = Path_Based_Clustering( D, 60, 10, 15, 2);
% Labels are the output of clustering algorithm.
```

| ON Entry | Description          |
| ------------- | ----------- |
| data   | N*P data (N should be the number of data points and P is the number of variables)|
| k     |  Radius of epsilon graph or no neighbours |
| no_landmarks     |  Number of landmarks  |
| angle_constraint  |  Angel constraint used in shortest path algorithm|
| no_clusters   |  Number of clusters  |

|On Exit | Description  |
| ------------- | ----------- |
| labels      | Labels that computed using result of clustering algorithm  |
