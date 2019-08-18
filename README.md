# Training domain specific Word2Vec word embedding model with Gensim

<img src="a_word_by.JPG">

The vector of a word is a semantic representation of how that word is used in context. Word2Vec assumes two words that have the same context will also share the same meaning and therefore, both words will have similar vector representation.

Word2vec utilize two model architectures,continuous bag-of-words (CBOW) or continuous skip-gram. The model that uses continuous bag-of-words, current word is predicted from a window of surrounding context words. The order of surrounding words does not influence prediction.

In the case of continuous skip-gram architecture, the the current word in the model is used  to predict the surrounding window of the context words. The skip-gram architecture gives more weight to nearby words than distant words. CBOW is faster than skip-gram but skip-gram performs a better when it comes to infrequent words.

<img src="foreclosure.JPG">
