# Bakery-Transaction-Analysis
*Authors: Shuoqi Zhang, Trista Lin.*

## Objectives: 
* To analyze the association rules of items purchased and to define actions to boost the sales.
* To predict the number of transactions at a given time in hour and to provide insights about how external variables impact the sales.
* To identify and explain any possible segment of transactions.

## Data Source:
* CSV dataset of transaction records of a bakery located in the old town of Edinburgh, UK (https://www.kaggle.com/sulmansarwar/transactions-from-a-bakery)
* Weather-related data were extracted from Meteostat (a Python library, https://dev.meteostat.net/python/hourly.html#example)

## Data Cleaning: 
* The cleaned dataset was splitted into weekday and weekend datasets due to different patterns observed. Results from weekend data are illustrated as examples below.

## Data Analysis I: Market Basket Analysis
![Which items are often purchased together?](popularity.png)


## Data Analysis II: Random Forest
![Which features predict the sales?](/plot/hotmap/avg_rate_nyc.png)


## Data Analysis III: K-means Clustering
![What are the optimal number of clusters?](/plot/hotmap/avg_rate_nyc.png)






![What are the characteristics of each cluster?](/plot/hotmap/avg_rate_nyc.png)
