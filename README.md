# Project Description

In this project, I want to cluster the dataset into a few distinctive groups using K-Means algorithm and Auto Encoder to find and split the data into optimal distinctive groups. For finding the optimal number of cluster, I use the elbow method. After that, i applying Principal Component Analysus and visualize the results

## Dataset

Dataset: [AI in Marketing](https://www.kaggle.com/kyanyoga/sample-sales-data)

This Dataset contains 2823 data of 24 columns.

## Model

Before using K-Means algorithm, I got 5 cluster. The explaination for the 5 cluster was :
1. Cluster 0 (Highest) - This group represents customers who buy items in high quantity centered around ~47, they buy items in all price range leaning towards high price items of ~99. They also correspond to the highest total sales around ~8296 and they are active throughout the year. They are the highest buyers of products with high MSRP ~158.
2. Cluster 1 - This group represents customers who buy items in varying quantity ~35, they tend to buy high price items ~96. Their sales is bit better average ~4435, they buy products with second highest MSRP of ~133.
3. Cluster 2 (lowest) - This group represents customers who buy items in low quantity ~30. They tend to buy low price items ~68. Their sales ~2044 is lower than other clusters and they are extremely active around holiday season. They buy products with low MSRP ~75.
4. Cluster 3 - This group represents customers who are only active during the holidays. they buy in lower quantity ~35, but they tend to buy average price items around ~86. They also correspond to lower total sales around ~3673, they tend to buy items with MSRP around 102.
5. Cluster 4 - This group represents customers who buy items in varying quantity ~39, they tend to buy average price items ~94. Their sales ~4280.

After using K-Means algorithm, I got 3 cluster. The explanation for the 3 cluster was :
1. Cluster 1 - This group represents customers who buy items in varying quantity ~37, they tend to buy high price items ~95. Their sales is bit better average ~4398, they buy products with second highest MSRP of ~115.
2. Cluster 2 (lowest) - This group represents customers who buy items in low quantity ~30. They tend to buy low price items ~69. Their sales ~2061 is lower than other clusters and they are extremely active around holiday season. They buy products with low MSRP ~77.
3. Cluster 0 (Highest) - This group represents customers who buy items in high quantity centered around ~47, they buy items in all price range leaning towards high price items of ~99. They also correspond to the highest total sales around ~8293 and they are active throughout the year. They are the highest buyers of products with high MSRP ~158.