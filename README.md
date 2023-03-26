# K-means_Customer_Segmentation
## Introduction
Customer segmentation is one of the most important applications of unsupervised learning. Clustering techniques allow companies to identify different customer segments and target their potential user base. This machine learning project uses K-Means clustering, an essential algorithm for clustering unlabeled datasets. Before proceeding with this project, let's learn what  customer segmentation really is. 

Customer segmentation  means grouping  customers by different characteristics (for example, grouping customers by age).
It's a way for companies to understand their customers. Knowing the differences between customer groups facilitates strategic decisions related to product growth and marketing.
The possibilities for segmentation are endless and mostly depend  on the amount of customer data  at your disposal.Starting from  basic criteria like gender, hobbies, age, etc., to "time spent on website X" and " The time since the  user opened the app”.

 ![image](https://user-images.githubusercontent.com/85514219/222490471-7767096f-c1c8-467b-a06a-ba03a4feb291.png)

## K-Means Clustering
K-Means clustering is an efficient machine learning algorithm to solve data clustering problems. It’s an unsupervised algorithm that’s quite suitable for solving customer segmentation problems. Before we move on, let’s quickly explore two key concepts

## Unsupervised Learning
Unsupervised machine learning is very different from supervised machine learning. It is a special type of machine learning algorithm that detects patterns in datasets of unlabeled data. Unsupervised machine learning algorithms can group data points based on similar attributes in the data set. One of the main types of unsupervised models is the clustering model.

## Clustering algorithms
Clustering machine learning algorithms are unsupervised machine learning algorithms. It is used to discover natural groupings or patterns within a data set. Note that the  clustering algorithm only interprets the input data and finds natural clusters within it.
Some of the most popular clustering algorithms are:  

1. K-Means Clustering
2. Agglomerative Hierarchical Clustering
3. Expectation-Maximization (EM) Clustering
4. Density-Based Spatial Clustering 
5. Mean-Shift Clustering

## K-means algorithm 
The K-Means algorithm is an iterative algorithm that attempts to divide a data set into K pre-defined, non-overlapping subgroups (clusters) where each data point belongs to only one group. It tries to make the data points in clusters as similar as possible while keeping the clusters as distinct (width) as possible. Data points are assigned to clusters so that the sum of squared distances between the data points and the centroids of the clusters is minimized. The less variation within a cluster, the more uniform the data points within the same cluster. Next, we performed K-Means clustering. This creates different clusters for grouping similar spending activities based on age and annual income. KMeans clustering selects random values ​​from the data and forms related clusters. We took the closest values ​​from the center of each cluster to update the clusters and reshape the plot (similar to k-NN). The closest value is based on Euclidean distance.

## Dependencies

1. Pandas
2. NumPy
3. Matplotlib
4. Seaborn
5. Sklearn

Install missing dependencies using,

    pip install pandas numpy matplotlib seaborn sklearn

## Results
### Before applying K-means
![customer segmentation 2](https://user-images.githubusercontent.com/85514219/227789260-837582ef-629d-4c9b-ab36-4eec1b669bfa.png)

### After applying K-means
Found the best K using elbow-method
![customer segmentation 1](https://user-images.githubusercontent.com/85514219/227789301-b94094e2-0f93-48db-b4cb-0a262dce2874.png)

## Thank you
