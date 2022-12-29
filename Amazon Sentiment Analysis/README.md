# Overview
* Built and trained a Random Forest Classifier (RFC) and a Convoutional Neural Network (CNN) on amazon reviews to predict sentiment.
* Processed the reviews by tokenizing, removing stopwords, and lemmatizing to analyze the text.
* Used TF-IDF to rank the importance of words and trained the RFC on it.
* Optimized models using GridSearch.
* Created functions to scrape Amazon reviews based on user input of a product review page and applied the models to these reviews.

## Code and Resources Used
**Python Version:** 3.9 <br>
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn, joblib, pickle, bz2, nltk, tensorflow

## Results
Random Forest Classifier
* Accuracy = 0.83
* Recall = 0.83
* Precision = 0.84
* ROC-AUC = 0.83

Convolutional Neural Network
* Accuracy = 0.93
* Recall = 0.92
* Precision = 0.94
* ROC-AUC = 0.98

## Conclusions
* The CNN model seemed to be the superior model, when it came to predicting the sentiment of Amazon reviews.
* The CNN model scored higher on all metrics and, when tested on live data, was able to more pick up on more negatively loaded terms.
* Despite coming up short, the RFC model still performed decently across all metrics.
* From our analysis on the toothbrush, a consumer would be able to glean the following:
 * The toothbrush has a majority positive reception from other consumers.
 * The main benefits of the toothbrush revolve around its cleaning ability, application, and gentleness/sensitivity.
 * The main issues regarding the toothbrush seem to revolve around its price, battery life, and application. 
