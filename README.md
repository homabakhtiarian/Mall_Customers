# Hierarchical Clustering

An example of clustering with hierarchy is taxonomy of the animal kingdom.
For instance there is the general term Animal. Sub-clusters are fish, mammals and birds. For instance there
are birds which can fly and those that can't. We can continue in this way until we reach dogs and cats. Even then we can divide dogs and cats into different breeds.
Moreover some breeds have sub-breeds. This is called hierarchy of clusters. There are two types of hierarchical clustering agglomerative or bottom up and divisive or top down.
With divisive clustering we start from a situation where all observations are in the same cluster like
the dinosaurs then we split this big cluster into two smaller ones.
Then we continue with three, four or five and so on until each observation is in separate cluster.
However in order to find the best split we must explore all possibilities at each step.
Therefore faster methods have been developed such as K-means. With K means we can simulate this divisive technique and that's what we do with the elbow method.
We start with one cluster then two, three, and so on. While the graph show us when we should stop increasing the number of clusters  when it comes to
agglomerative clustering the approach is bottom up. We start from different dog and cat breeds and cluster them into dogs and cats respectively and then we continue pairing up species until we reach the animal cluster.
Agglomerative and divisive clustering should reach similar results but agglomerative is much easier to solve mathematically.
In order to perform agglomerative hierarchical clustering we start with each case being its own cluster.
There is a total of n clusters. Second using some similarity measure like Euclidean distance, we group the two closest clusters together reaching n-1 cluster solution.
Then we repeat this procedure until all observations are in a single cluster.

