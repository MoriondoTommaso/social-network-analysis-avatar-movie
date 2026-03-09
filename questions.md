# Week 1-2-3

## Week 1

1) Pick a social network among the one proposed on luiss.learn

2) Implement it in Python.

3) Draw the graph

4) Compute the number of nodes,edges, average degree and the density. Comment.

**Be careful if the network that you have picked is directed or not.**

## Week 2:

**While considering the largest component of your network.**

1) Design a function computing the clusering at every nodes and another on that computes the average clustering.

2) Compare to inbuild function Compute Average clustering and Transitivity number,

## Week 3:

1) Compute the cumulative distribution of the clustering

2) Define for every node the average of clustering of its neighbors. Compute the cumulative distribution

3) Compare the two distributions.

# Week 5-6-7
## Week 5 

1) Depending on what seems more relevant in your graph, pick two of the following local notions

Decay centrality
Betweeness centrality
Closeness centrality
Any other notions that you invent
Pagerank
2) Identify the most central nodes.

 
## Week 6 

Treat your graph as undirected and unweighted. Delete loops and work on the resulting largest connected component.

 Implement two of the following three techniques for community detection:

a) Bridge removal (pick the partition with the highest modularity)

b) Modularity optimization


c) Label propagation.

In this case, you are allowed to use built-in functions from NetworkX.
Discuss which one you think is the best and why.

 Provide a visualization for the partition you decided to be the best using Gephi ( https://gephi.org/gephi-lite/)

## Week 7

Treat your graph as undirected and unweighted, and work on the resulting largest connected component. Delete loops

 Create a function computing CN and one of the topological indices between JI,PA,AA,RA. Your function should return a pandaframe where each row is a missing link and each column is an index. You are allowed to use built-in functions from NetworkX for computing individual indices.

Create a third score by adding a column with the sum of the two indices. [NB: the arithmetic mean should be computed after rescaling each column between 0 and 1.

For each of the 3 scores, identify as missing links the node pairs yielding the largest 5/10 values. Briefly comment the results.