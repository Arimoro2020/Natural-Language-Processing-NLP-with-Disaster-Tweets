# Natural-Language-Processing-NLP-with-Disaster-Tweets
Building a machine learning model that predicts which Tweets are about real disasters and which ones are not.

Definition of Problem: This is a binary classification problem that predicts which Tweets are about real disasters and ones which are not so that agencies involved in disaster relief, and news broadcast programatically monitoring Twitter are able to act decisively with more confidence.
.

Dataset: Dataset of 10,000 tweets that were hand classified as real-disasters(1) and not real(0) in which the author explicitly uses the words associated with disaster. The dataset for may contain text that may be considered profane, vulgar, or offensive.



Feature Engineering:


Data Cleansing: The tweets was processed to return list of words(Tokens), cleaned by removing punctiations and stopwords, and the tokens processed further by grouping together the inflected forms of a word so that they are analyzed as a single term/word (lemmatizing).
