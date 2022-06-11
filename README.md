# Neural-TweetCorp
Feedforward neural network

Build classifiers to assess the sentiment of texts. Train models on a dataset from a TweetCorp corpus

To solve the problem, it is necessary to use 3 sets of features:
  1. Signs based on the results of morphological analysis of texts - the proportion of various parts of speech (adjectives, nouns, verbs, interjections, etc.)
  2. Linguistic features obtained using the tone dictionary.
  3. Based on the "bag of words" model with the TF-IDF measure.
  
For each set of features, build a classifier using a feed-forward neural network.
