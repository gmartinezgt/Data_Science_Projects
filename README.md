# House Prices Prediction
Built three models, consisting of linear, elastic, and random forest regression models, to predict house prices based on descriptive features of the property. After cleaning the dataset, the models were trained, tested, and then compared on several metrics.

## Findings
Random forest regression was the best performing model across all the measures with an impressive R<sup>2</sup> of 0.90.

# Customer Segmentation
Using a comapny's customer dataset, this project attempts to cluster unique groups of customers based on variables, such as income, expenses, marraige status, and more. After cleaning and engineering features, the data was processed through PCA and then two clustering algorithms, agglomerative clustering and K-Means, were performed to identify groups of customers.

## Findings
Found four clusters of customers that differ on income, expenditure, children, and how likely they are to participate in promotional campaigns and special deals.

# Amazon Review Sentiment Analysis
This project allows users to enter a product url and receive sentiment analysis of hundreds or even thousands of reviews. Two models, Random Forest Classifier (RFC) and Convolutional Neural Network (CNN), were trained on thousands of pre-labeled reviews, evluated, validated, and then applied on scraped reviews of the product page of choice.

## Findings
The CNN model was significantly better across all metrics (accuracy, precision, recall, and ROC-AUC). As a result, the CNN model seemed to pick out words that were more informative based on its predicted sentiment in the resulting wordclouds.
