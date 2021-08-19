# Rating-Predictions
The model predicts ratings of online product reviews
EDA was done by:
1. plotting the distribution of rating frequency of the reviews.rating column.
2.The types of word people use in their reviews through Wordcloud by Stopwords.
3.Identifying the popular categories and the popular products that have been purchased.
4.Latent Semantic Analysis through Count Vectorizer model
Cleaning of data was done by:
1.Identify and removing null values for reviews text.
2.Sorting out duplicate reviews.
3.Removing the stop words.
4.Filtered 1 star and 5 star ratings for analysis

2.Independent and dependent feature:
Independent Feature: Review Text
Dependent Feature: Review rating

3.  n-gram Tfidf vectorizer:

Used a Tfidf Vectorizer to extract only a subset of n-grams for the model by a set of parameters

4.Model, Accuracy:
Logistic regression model was used with a K-fold cross-validation
Each k folds is given an opportunity to be used as a held back test data, while all other folds collectively are used as a training dataset.
Accuracy: 0.7327137022954513
