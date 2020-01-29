In this project using data of customers from a retailer, I've segmented customers in 5 categories using K-Means Clustering.

I analysed the optimal number of clusters using Silhouette Analysis and Sum of Squared Errors (Elbow) and then visualized the 
clustered data using PCA (2D decomposition).

Further as a datascientist I shouldn't just cluster the customers. Thus, I analysed each cluster of customers and came up with 
some insights which can be used as marketing startegies. These insights can be further developed by the business asociates of 
the company.

------------------------------------------------------------------------------------------------------------------

Summary of Strategies

After the analysis we can see that there are 5 different kinds of customers.
1) Cluster 1: 1st category is of those customers in a young age group (20-35) avg age of 24. They have low annual income of $26K but there spending score is high. This contains more of females

2) Cluster 2: 2nd category is of those customers diverse age group (20-65) avg age of 41. They have average annual income of $55K and there spending score is also average. This also contains more of females

3) Cluster 3: 3rd category is of those customers diverse age group (20-55) avg age of 38. They have good annual income of $87K but there spending score is low. This contains more of males

4) Cluster 4: 4th category is of those customers diverse age group (20-65) avg age of 43. They have low annual income of $26K and there spending score is also low. This contains more of females.

5) Cluster 5: 5th category is of those customers diverse young group (20-40) avg age of 30. They have high annual income of $86K and there spending score is also high. This contains more of females but not large.


Devised Strategies:

1) Strategy for group 1: they have high spending score but low income so we should target them with cheaper products as they don't have the income to afford expensive products. 

2) Strategy for group 2: these people have average spending score and average incomes. We need to show them value in the product and give them some good deals.

3) Strategy for group 3: these people have good income but low spending score. These are our potential customers who even have the power to spend. We need to come up with offers to make them spend (for instance buy 1 get 1 offers)

4) Strategy for group 4: They have low income and their spending score is also low. I believe if we are running a limited campaign we can leave these customers as they neither have the spending power nor spending habit.

5) Strategy for group 5: They have high income and high spending scores. These are our consistent customers and to keep them consistent we need to make them believe that we care for them, by giving loyalty points, 24x7 customer service, free return policies, b'day gifts etc.
------------------------------------------------------------------------------------------------------------------

Code in https://github.com/karanm14/data_analysis/blob/master/customer_segmentation/Customer_Segmentation.ipynb 

------------------------------------------------------------------------------------------------------------------
Dataset Description: Mall_Customers.csv

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1-100)

------------------------------------------------------------------------------------------------------------------

Output File: Segmented_Customers.csv

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1-100)

cluster_label: Group to which customer belongs to
