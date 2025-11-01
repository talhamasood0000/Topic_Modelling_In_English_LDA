# Topic Modelling in English using LDA

## Overview
This project implements Latent Dirichlet Allocation (LDA) for topic modeling on English text documents. The implementation extracts hidden topics from a collection of academic papers using unsupervised machine learning techniques.

## Features
- Data preprocessing and text cleaning
- Word cloud visualization
- LDA model training with configurable topic numbers
- Interactive topic visualization using pyLDAvis

## Requirements
- Python 3.x
- pandas
- gensim
- nltk
- pyLDAvis
- wordcloud
- matplotlib

## Workflow
1. **Data Loading**: Loads academic papers from CSV file
2. **Text Preprocessing**: 
   - Removes punctuation and converts to lowercase
   - Tokenizes text using Gensim's simple_preprocess
   - Removes English stopwords
3. **Visualization**: Generates word cloud for exploratory data analysis
4. **Dictionary & Corpus Creation**: 
   - Creates word-to-id mapping using Gensim Dictionary
   - Converts documents to bag-of-words representation
5. **LDA Training**: Trains multicore LDA model with 10 topics
6. **Results**: Displays topic keywords and interactive visualization

## Output
- Topic keywords for each discovered topic
- Interactive pyLDAvis visualization for topic exploration
- Word cloud showing frequent terms in the dataset

## Usage
Run the Jupyter notebook `Topic_Modelling_In_English_LDA.ipynb` sequentially to execute the complete pipeline.
