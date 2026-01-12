# Text Preprocessing Pipeline Lab

## Overview
This repository contains a complete implementation of text preprocessing techniques for Natural Language Processing (NLP) using Python. The lab covers fundamental preprocessing steps including tokenization, stemming, lemmatization, stop word removal, and special character cleaning.

## Features
- ✅ Tokenization with NLTK and spaCy
- ✅ Stemming (Porter, Snowball) and Lemmatization (WordNet, spaCy)
- ✅ Stop word removal in multiple languages
- ✅ Special character and punctuation cleaning
- ✅ Complete preprocessing pipeline implementation
- ✅ Social media text cleaning (URLs, mentions, hashtags)

## Technologies Used
- Python 3.11+
- NLTK (Natural Language Toolkit)
- spaCy (Industrial-strength NLP)
- Regular Expressions (re)
- Jupyter Notebook

## Installation & Setup
```bash
# Clone the repository
git clone https://github.com/your-username/nlp-text-preprocessing-pipeline.git

# Navigate to project directory
cd nlp-text-preprocessing-pipeline

# Install required libraries
pip install nltk spacy

# Download NLTK data
python -m nltk.downloader punkt punkt_tab stopwords wordnet averaged_perceptron_tagger

# Download spaCy model
python -m spacy download en_core_web_sm
