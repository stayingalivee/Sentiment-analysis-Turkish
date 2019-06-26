# Sentiment analysis Turkish

0.1 version uses one-hot encoding technique and a one hidden layer neural network.
0.2 version uses word embedding layer in addition to a global average pooling 1D and a hidden layer.

Both versions uses tokenizing, and builds a vocabulary dictionary sorted by word frequencies (top 5000, but it's a variable).

in verstion 0.2 a TurkishStemmer library was tried but it added nothing to the overall accuracy. (Probably because The library sometimes produces unreliable results)

##TODO:
Handling stop words and using a proper stemmer.
