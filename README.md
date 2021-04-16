---

# WordClouds - Classification - Clustering

#### ✔️ Open this notebook with jupyter online viewer [jupyter nbviewer](https://nbviewer.jupyter.org/github/Nikoletos-K/Article-Classification-Clustering/blob/master/Project.ipynb) ✔️

__Language:__ python > 3.0

__Data:__ Articles from five different sections (business,entertainment, politics, sport, tech) of an news site.

This project consists of __2 main queries.__ 

## 1st Query | WordCloud creation
Given the text from the articles,we are making a text-cleaning and after we create some wordclouds for each category. Most common words can be now depicted.

## 2nd Query | Classification 
Working with:

- Classifiers: __Support Vector Machines (with GridSearchCV),Random Forests,Naive Bayes,K-Nearest Neighbor__
- __KNN__:  Custom implementation included

We are using 10-fold Cross Validation and scores: 
- Precision 
- Recall  
- F1-Score  
- Accuracy


__Visualization__
- ROC plots

## 3rd Query | Beat the Benchmark
Optimizing the Q.2 scores.

## 4th Query | Clustering

- For the clustering we use K-Means (numver of clusters=5)
- Pre-trained embeddings  (word2vec, glove, fast-text).
- Compressing the data to 2 dimnsions with PCA,ICA and SVD

---

© Konstantinos Nikoletos & Myrto Iglezou
