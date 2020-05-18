# Cryptocurrencies
### Module 18 Challenge

## Pre Process
This involves cleaning up the dataset to enable us to process the data using Unsupervised learning.

- Remove all cryptocurrencies that aren’t trading.
- Remove all cryptocurrencies that don’t have an algorithm defined.
- Remove the IsTrading column.
- Remove all cryptocurrencies with at least one null value.
- Remove all cryptocurrencies without coins mined.
- Conert TotalCoinSupply to Float64
- Store the names of all cryptocurrencies on a DataFramed named coins_name, and use the crypto_df.index as the index for this new DataFrame.
- Remove the CoinName column.
- Create dummies variables for all of the text features, and store the resulting data on a DataFrame named X.
- Use the StandardScaler from sklearn (Links to an external site.) to standardize all of the data from the X DataFrame. Remember, this is important prior to using PCA and K-means algorithms.

## Reducing Data Dimensions Using PCA
Break down the dimetions of the data into three Principal Components we will name: **PC1, PC2, & PC3** using the trading name as the index for our new data

## Clustering Cryptocurrencies Using K-means
With further analysis, and using a elbow curve, we determined that dividing into 5 clusters would give us a good result. WE then divide the cryptocurrencies into their individual classes

## Visualizing results
Create 3d Scatter plots using the Principal Components to show how the groups are clustered; This requires a 3D scattergraph due to us having three seperate components.

We also created a 2d Scatter plot to show the relationship between Total Coins Mined and Total Coin supply.

## Final Thoughts:
This allows us to look at how we may group the various Cryptocurrencies on the market today; WE can then further refine our research and find which of the many options would be worth our investment.
