# Twitterscan
The approach to implement this model is to:
  Train a custom Word2vec model on the tweet dataset. It will assign embeddings to every word within the corpus.
  Train a KMeans clustering algorithm to group similar meaning words in the same clusters. This gives us intuition about positive, negative, and neutral words.
  Compute the sentiments of a whole tweet by averaging out the sentiments of individual words within the tweet. Thus we get our labels.
