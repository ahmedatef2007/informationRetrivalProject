# Information Retrieval Project

## Overview
This Python script implements several techniques for information retrieval and analysis of text documents. It includes functionalities for tokenization, building positional indexes, calculating term frequencies (TF), inverse document frequencies (IDF), and generating vector space models (VSM). Additionally, it computes cosine similarity between documents and supports phrase queries.

## Features
- Tokenization: Splits text into tokens using regular expressions.
- Stopword Removal: Removes common stopwords from the tokenized text.
- Positional Index: Builds a positional index for terms in documents.
- TF-IDF Calculation: Computes term frequency-inverse document frequency values for each term in the documents.
- Vector Space Model (VSM): Constructs VSM representations for documents.
- Cosine Similarity: Measures similarity between documents based on their VSM representations.
- Phrase Query: Allows users to search for specific phrases across documents.
- Interactive Interface: Provides a simple command-line interface for user interaction.

## Usage
1. Ensure you have Python installed on your system.
2. Run the `main.py` script to execute the information retrieval functionalities.
3. Follow the prompts to choose options such as phrase query or exit.

## Files
- `main.py`: Entry point for running the information retrieval functionalities.
- `docs/`: Directory containing text documents for analysis.
- `README.md`: This file, providing an overview of the project.
- `requirements.txt`: Text file listing required Python libraries for installation.

## Dependencies
- Python 3.x
- Required libraries: `nltk`, `pandas`, `prettytable`, `scikit-learn`
