## Word2Vec – Analysis of Game of Thrones Text

This project explores **Natural Language Processing (NLP)** using **Word2Vec** to analyze textual data from *Game of Thrones*. The main objective is to learn meaningful word representations and understand relationships between words based on the context in which they appear.

The text data is first cleaned and preprocessed using techniques such as **tokenization, lowercasing, removal of unnecessary characters, and stopword removal**. A **Word2Vec model using the Gensim library** is then trained on the processed text to generate word embeddings.

The trained model is used to identify **similar words and semantic relationships** within the Game of Thrones vocabulary. Word vectors are further analyzed using **cosine similarity** to measure how closely different words are related.

Since Word2Vec produces high-dimensional vectors, **Principal Component Analysis (PCA)** is used to reduce their dimensionality and visualize selected word embeddings in a 2D space.

### Key Concepts

* Natural Language Processing (NLP)
* Text preprocessing and tokenization
* Stopword removal
* Word2Vec and word embeddings
* Gensim
* Cosine similarity
* PCA dimensionality reduction
* Word-vector visualization

This project demonstrates how Word2Vec can transform textual information into numerical representations while preserving semantic relationships between words.

