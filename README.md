# Amazon-Fine-Food-Reviews
A rolling case study that contains implementation of supervised and unsupervised learning algorithms.

**About the dataset:**

The Amazon Fine Food Reviews dataset is available on [kaggle](https://www.kaggle.com/snap/amazon-fine-food-reviews). The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.
Number of reviews: 568,454
Number of users: 256,059
Number of products: 74,258
Timespan: Oct 1999 - Oct 2012
Number of Attributes/Columns in data: 10

I have done basic EDA but for a detailled EDA please check out this [link](https://nycdatascience.com/blog/student-works/amazon-fine-foods-visualization/)

Of all the features available, we only considered the ones with textual data (Reviews and for feature engineering Summary) for our predictive modelling. We have used following **vectorization techniques** to convert text into its vector form:

1. Bag of Words
2. TF-IDF
3. Average word2vec
4. TF-IDF weighted word2vec


**Objective**:

Given a review, determine whether the review is positive (rating of 4 or 5) or negative (rating of 1 or 2)

**The Supervised Learning Algorithms used are:**
1. Decision Trees
2. kNN
3. Logistic Regression
4. Navie Bayes
5. Random Forest, Gradient Boosting Decsion Trees, lightGBM
6. Support Vector Machine

**The Unsupervised Algorithms used are:**
1. k-Means 
2. Hierarchical Clustering
3. DBSCAN 
4. Truncated SVD
5. Dimensionality reduction technique: t-sne
