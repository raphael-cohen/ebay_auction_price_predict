# ebay_auction_price_predict
Predicting prices for ebay auction (R language)


Overview
Online auctions are one the most popular methods to buy and sell items on the internet.
With more than 100 million active users globally, eBay is the world's largest online
marketplace, where practically anyone can buy and sell practically anything. The total
value of goods sold in Q4 of 2011 on eBay was $68.6 billion, more than $2,100 every
second ​[1]​. This kind of volume produces huge amounts of data that can be utilized to
provide services to the buyers and sellers, market research, and product development.
In this analysis, we use the historical eBay Auctions dataset to predict the likelihood of
an item being sold, and the final selling price for these items. The dataset used contains
~300,000 auction items in the train and test datasets from the sports autograph
category on eBay.​[data link]
In this paper we are trying to answer two broad questions: (a) Can we predict the
likelihood of an auction item getting sold, and (b) Can we predict the final selling price of
an auction item, given information on its category, starting bid value and so on.
For the first part, we have implemented and optimized three popular classification
algorithms, namely Logistic Regression, Random Forest and Linear Discriminant
Analysis. We aim to optimize all three algorithms, and complete a comparative study of
the performance improvements within each algorithm. To predict the final selling price,
we have implemented Multiple Linear Regression, and the final approach involves
identifying clusters within our dataset, and fitting a separate regression model on each
cluster. Several tests have been performed to test the suitability of each method and to
reduce the overall error rate.


See full report for details
