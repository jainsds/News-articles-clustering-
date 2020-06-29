# Overview
1. Text prepreprocessing - Removing stopwords ,most commonly occuring words,URL's from the text
2. Embedding - I used Doc2Vec to convert each news article into 100 dimensional vector
3. Clustering - I tried clustering the vectors using GMM and Kmeans .I plotted the accuracy plot for both GMM and Kmeans by predicting on test data with labels
4. Results - I achieved highest accuracy of 60.5% using Kmeans with 17 clusters achieved.
