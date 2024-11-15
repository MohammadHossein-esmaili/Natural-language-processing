#    **Natural-language-processing**
## Natural Language Processing (NLP) with Python
This repository contains various Python scripts demonstrating key techniques in Natural Language Processing (NLP). The code includes different tasks such as tokenization, stemming, lemmatization, Named Entity Recognition (NER), and text classification, all using popular Python libraries like NLTK, spaCy, gensim, and scikit-learn.

Features
Tokenization:

Sentence Tokenization: Splitting text into individual sentences.
Word Tokenization: Splitting sentences into individual words.
Text Preprocessing:

Lowercasing: Converting all text to lowercase for normalization.
Stopword Removal: Filtering out common words like "the", "is", "in", etc., which do not carry significant meaning.
Stemming & Lemmatization:

Porter Stemming: Reducing words to their root form using the Porter algorithm.
Snowball Stemming: An alternative stemming algorithm with improved handling of different languages.
Lemmatization with spaCy: Reducing words to their base or dictionary form using spaCy's advanced lemmatizer.
Regular Expressions:

Phone Number Extraction: Using regular expressions to extract phone numbers from a text.
Email Address Extraction: Using regular expressions to extract email addresses.
Text Vectorization:

Count Vectorization (BoW): Converting text into a matrix of token counts.
TF-IDF Vectorization: Converting text into a matrix of term frequency-inverse document frequency values.
Word Embeddings & Visualization:

Word Embedding with GloVe: Using pre-trained GloVe word vectors to find similar words and visualize them in 2D space using PCA.
Libraries Used
This project uses the following Python libraries:

nltk for text processing and tokenization.
spacy for advanced NLP tasks like lemmatization and named entity recognition.
gensim for working with word embeddings.
sklearn for vectorizing text using CountVectorizer and TfidfVectorizer.
matplotlib for plotting visualizations.
