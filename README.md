### Amazon Reviews - Sentiment Analyser

This project analyses the Amazon review dataset from Datafinity's Kaggle page and provide sentiment of the review. This uses **Python** library _Spacy_ to work out the sentiment score. Since the model used is not as adcanced as LLM model, there are false positives and false negatives in some cases.

## Table of contents 
    1. sentiment_analysis.ipynb - Code which fetches the amazon review file and provides the sentiment for Top 1000 reviews. This has a function to provide sentiment of any text 
    2. sentiment_analysis_report.pdf - This document analyses some of the results and shortcomings

## Installation 
    pip install spacy
    pip install spacytextblob
    python -m textblob.download_corpora

## Usage 
  1. Download the sentiment_analysis.ipynb
  2. Upload to your local Jupyter server
  3. Change the path of the amazon review file
  4. If you want to just use the sentiment_analysis function, you can simply use the function directly for any text you have (not just the amazon review text)
  
