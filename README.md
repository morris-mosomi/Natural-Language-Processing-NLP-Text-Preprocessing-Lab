# Natural Language Processing (NLP) Text Preprocessing Lab

## Overview

This project demonstrates a complete Natural Language Processing (NLP) preprocessing pipeline using Python. The notebook applies several text preprocessing techniques to hotel reviews, then performs sentiment analysis and evaluates the effectiveness of each preprocessing step.

This project showcases practical NLP skills including text cleaning, tokenization, lemmatization, n-gram generation, and sentiment analysis using NLTK.

---

## Project Objectives

- Clean and normalize raw text
- Tokenize text into words
- Remove stopwords
- Perform Part-of-Speech (POS) tagging
- Apply WordNet lemmatization
- Generate bigrams and trigrams
- Analyze frequently occurring terms
- Perform sentiment analysis using VADER
- Evaluate the preprocessing pipeline

---

## Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- NLTK
- Matplotlib
- Seaborn

---

## Project Workflow

1. Load the dataset
2. Clean and normalize text
3. Tokenize reviews
4. Remove stopwords
5. Perform POS tagging
6. Apply lemmatization
7. Generate bigrams and trigrams
8. Analyze word frequencies
9. Perform sentiment analysis using VADER
10. Evaluate preprocessing results

---

## Features

- ✔ Text Cleaning
- ✔ Tokenization
- ✔ Stopword Removal
- ✔ POS Tagging
- ✔ Lemmatization
- ✔ N-gram Generation
- ✔ Frequency Analysis
- ✔ VADER Sentiment Analysis
- ✔ Vocabulary Reduction Analysis

---

## Installation

Clone the repository:

Install the required libraries:

```bash
pip install pandas numpy nltk matplotlib seaborn
```

Download the required NLTK resources:

```python
import nltk

nltk.download("punkt")
nltk.download("stopwords")
nltk.download("wordnet")
nltk.download("omw-1.4")
nltk.download("averaged_perceptron_tagger_eng")
nltk.download("vader_lexicon")
```

---

## Results

This project demonstrates how NLP preprocessing improves text quality by reducing vocabulary size, normalizing words through lemmatization, and extracting meaningful linguistic patterns for sentiment analysis.

---

## Future Improvements

- TF-IDF Vectorization
- Word Embeddings (Word2Vec, GloVe)
- Transformer Models (BERT)
- Topic Modeling
- Machine Learning Text Classification

---

## Author

**Morris Mosomi**

---

## License

This project is licensed for educational purposes.
