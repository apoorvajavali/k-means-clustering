# k-means-clustering

# Objectives:
 Compute the similarity between tweets using the Jaccard Distance metric.
 Cluster tweets using the K-means clustering algorithm
 
Here is the reference for more details about Jaccard Distance:
http://en.wikipedia.org/wiki/Jaccard_index
 
 #  Pre-processing steps:
- Remove the tweet id and timestamp
- Remove any word that starts with the symbol @ e.g. @AnnaMedaris
- Remove any hashtag symbols e.g. convert #depression to depression
- Remove any URL
- Convert every word to lowercase
