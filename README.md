# 2016-Campaign-Data-Analysis

File 1: Data Cleaning and Analytics

Cleaned the data, deleted all retweets, kept only hashtags and handles.
Removed users that have less than 20 tweets.

Data Analysis by Visualization

1. Plotted the number of the tweets against top-30 locations with the most tweets.

2. Showed the respective tweet word clouds of the top-3 locations with the most tweets.

3. Plotted the number of the tweets against top-50 users with the most tweets.

4. Showed the respective tweet word clouds of the top-3 users with the most tweets.

5. Plotted the occurrences of the top-100 most frequent hashtags/handles in the cleaned data

6. Showed the tweet word cloud of all the hashtags/handles in the cleaned data

File 2: Clustering

Merged ground truth class.

Ran k-means algorithm.

Computed confusion matrix, precision, recall and F-measure for K-means and agglomerative clustering. 

File 3: Classification

Removed all retweets and all users that have less than 20 tweets. 

use train_test_split() to split data into training and test sets, 20 percent of records go to test set.

Trained Decision Tree, SVM, Logistic Regression, and Neural Networks.

Trained K-NN model, performed parameter tuning.

Applyed 5-fold cross validation and used grid search to find the best K value for K-NN model.

Computed confusion matrix, precision, recall and F-measure.
