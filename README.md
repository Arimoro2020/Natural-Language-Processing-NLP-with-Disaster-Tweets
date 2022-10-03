# Natural-Language-Processing-NLP-with-Disaster-Tweets
Building a machine learning model that predicts which Tweets are about real disasters and which ones are not- This is a submission for an open Kaggle competion with rolling leaderbord.



Definition of Problem: This is a binary classification problem that predicts which Tweets are about real disasters and which ones are not so that agencies involved in disaster relief, and news agencies programatically monitoring Twitter are able to act decisively with more confidence.
.


Dataset: Dataset has about 10,000 tweets that were hand classified as real-disasters(1) and not real(0) in which the author explicitly uses a word associated with disaster. The dataset may contain text that may be considered profane, vulgar, or offensive.



Feature Engineering: Two new features were created from the tweets, namely text(tweet) length and percentage of punction in tweet. A third feature, which is a cross feature of the tweet length and the percentage punctuation was also created.



Data Cleansing: The tweets were processed to return list of words(Tokens), cleaned by removing punctiations and stopwords, and then processed further by grouping together the inflected forms of a word so that they are analyzed as a single term/word (lemmatizing).



Model Building: The cleaned tweets were encoded as integers to create feature vectors for Machine Learning by using count vectorization with N-grams(1,2). The model is based on the Multinomial Naive Bayes Classifier. The submission on Kaggle, evaluated as F1 score is 0.80416. This is a useful model because the 'benchmark'is set at 0.78179
