# Customer-Analytics-Python-
The STP framework of marketing is the backbone of this machine learning project. Segmentation is done using unsupervised learning algorithms and supervised learning determines the most fruitful segments for targeting and positioning of products in the future.

For segmentation, hierarchical clustering is perfromed which return a linkage matrix, which then is plotted using dendrogram.

![index](https://user-images.githubusercontent.com/26453844/115722519-849a6700-a398-11eb-8fdf-063c9e38f232.png)


Perform K-means clustering. I have considered 1 to 10 clusters, so the for loop runs 10 iterations.
 In addition the algortihm runs at many different starting points(using init=kmeans++).
 
![kmeans](https://user-images.githubusercontent.com/26453844/115722527-86642a80-a398-11eb-9ec8-d0472e4280cf.png)



Note I figure out optimized number of clusters.

![WCSS](https://user-images.githubusercontent.com/26453844/115724184-29697400-a39a-11eb-9158-db9f0a3c803e.png)

Now I create a new data frame with the original features and add the PCA scores and assigned clusters. PCA is used to reduce the dimension and get rid of unnecessary varaibles.

![pca_components](https://user-images.githubusercontent.com/26453844/115722535-882dee00-a398-11eb-9dc4-3867deec636a.png)

