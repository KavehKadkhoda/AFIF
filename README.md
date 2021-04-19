# AFIF
AFIF: Automatically Finding Important Features in Community Evolution Prediction for Dynamic Social Networks

We present AFIF, an efficient solution to examine communities' structural features and also to find a proper subset of promising features in order to predict the upcoming changes of social networks. 

In this work, we study social networks at a community structure level to predict communities' evolution over time. 

AFIF chooses an appropriate subset of features in prediction of community evolution while maintaining an impressive performance.

![image](https://user-images.githubusercontent.com/82231238/115204097-5e14cb80-a10d-11eb-89c0-208e1e826a69.png)

Community evolution prediction: (a) dividing the social network into time windows, (b) detecting communities in each time window, (c) utilizing a community tracker for community matching and identifying chains of community evolution, and (d) concepts of features, output variable, and time window t (the youngest time window) in training a classifier.


Table - Features of a community.
Feature	Explanation
Algebraic connectivity	Second smallest eigenvalue of a community's Laplacian matrix.
Average clustering	Average of vertices’ local clustering, and local clustering of a vertex is the fraction of triangles that actually exist over all possible triangles in its neighborhood.
Average neighbor degree	Average of vertices’ average neighbor degree in a community.
Betweenness	Average of vertices’ betweenness in a community, and betweenness of a vertex is the sum of the fraction of all shortest paths that pass through it.
Clique number	Size of the largest clique in a community.
Closeness	Average of vertices’ closeness in a community, and closeness of a vertex is the reciprocal of the average shortest path distance to it, over all n-1 reachable vertices.
Constraint	Average of vertices’ constraint in a community, and constraint of a vertex v is a measure of the extent to which the vertex v is invested in those vertices that are themselves invested in the neighbors of v.
Core number	Average of vertices’ core number in a community, and core number of a vertex is the largest value k of a k-core containing that vertex; a k-core is a maximal subgraph that contains vertices of degree k or more.
Degree assortativity	Measures the similarity of connections in a community with respect to the degree of vertices.
Density	Measured by 2e⁄(v(v-1)) where e is the number of edges and v is the number of vertices in a community.
Diameter	It is the maximum eccentricity, and eccentricity of a vertex v is the maximum distance from v to all other vertices in a community.
Edge	Number of edges in a community.
Edge betweenness	Average of edges’ edge betweenness in a community, and betweenness of an edge is the sum of the fraction of all shortest paths that pass through that edge.
Effective size	Average of vertices’ effective size in a community, and effective size of a vertex’s ego network is based on the concept of redundancy. A vertex’s ego network has redundancy to the extent that its contacts are connected to each other as well, and non-redundant part of a vertex’s relationships is the effective size of its ego network.
Estrada index	Topological index of folding or 3D compactness of a community.
Evolution	Structural changes within a community (see Fig. 3).
Global efficiency	Average of all pairs of vertices’ efficiency in a community, and efficiency of a pair of vertices is the multiplicative inverse of shortest path distance between the vertices.
Harmonic centrality	Average of vertices’ harmonic in a community, and harmonic of a vertex is the sum of reciprocal of shortest path distances from all other vertices to it.
Katz	Average of vertices’ katz in a community, and katz computes the centrality for a vertex based on the centrality of its neighbors.
Load centrality	Average of vertices’ load in a community, and load of a vertex is the fraction of all shortest paths that pass through that vertex.
Local efficiency	Average of vertices’ local efficiency in a community. Efficiency of a pair of vertices is the multiplicative inverse of shortest path distance between the vertices, and local efficiency of a vertex is the average global efficiency of subgraph induced by neighbors of the vertex.
Node connectivity	Minimum number of vertices that must be removed to disconnect a community or render it trivial.
Number of cliques	Number of maximal cliques in a community.
Page rank	Average of vertices' page rank in a community, and page rank computes a ranking of vertices in the community based on structure of incoming links.
Second order	Average of vertices' second order in a community, and second order of a given vertex is the standard deviation of return times to that vertex of a perpetual random walk on the community.
Size	Number of vertices in a community.
Square clustering	Average of vertices' square clustering in a community, and square clustering of a vertex is the fraction of possible squares that exist at the vertex.
Transitivity	Fraction of all possible triangles present in a community.
Wiener index	Sum of shortest-path distances between each pair of reachable vertices in a community.




