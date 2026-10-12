# Ebook Text & Sentiment Analysis

An exploratory Natural Language Processing (NLP) project that parses, cleans, and analyzes the text of an entire ebook using Python. 

## Overview
This project processes raw book text to extract structural elements, calculate meaningful word frequencies, and map the emotional arc of the narrative chapter-by-chapter. It serves as a practical application of data cleaning, regular expressions, and sentiment analysis.

## Core Features
* **Regex Data Extraction:** Uses regular expressions to dynamically split the raw `.txt` file into structured chapters and extract specific sentences based on word matching.
* **Text Cleaning & Stopword Filtering:** Cleans the raw text and utilizes `nltk` corpora to filter out common English filler words (stopwords), isolating the most structurally significant vocabulary.
* **Sentiment Analysis:** Employs the `nltk` VADER (Valence Aware Dictionary and sEntiment Reasoner) lexicon to calculate polarity scores (positive, negative, neutral, and compound) for individual sentences and entire chapters.

## Tech Stack
* **Language:** Python
* **Environment & Package Management:** `uv`
* **Libraries:** `re` (Regular Expressions), `nltk` (Natural Language Toolkit)
* **IDE:** JupyterLab / VS Code

This project uses `uv` for fast dependency management. 
