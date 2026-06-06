# Web Scraping & Natural Language Processing (NLP) Toolkit

## Project Overview
This repository is a curated collection of Python-based tools and demonstrations for **Web Scraping** and **Natural Language Processing (NLP)**. It showcases the end-to-end process of extracting raw data from the web and applying sophisticated linguistic algorithms to analyze and classify text.

## What is this Project?
The repository is organized into two primary domains:

### 1. Web Scraping
Focuses on the automated retrieval of data from various online sources.
- **Automated Extraction:** Includes scripts like `select_in_scraping.py` that demonstrate how to programmatically navigate and extract specific data points from HTML.
- **Data Collections:** Practical examples such as `weather_data.ipynb` for scraping real-time environmental data.

### 2. Natural Language Processing (NLP)
A deep dive into the mechanics of text analysis and machine learning for language.
- **Text Preprocessing:** Dedicated notebooks for **Tokenization**, **Stemming**, **Lemmatization**, and Stopword removal.
- **Feature Engineering:** Implementations of **Bag of Words** and **TF-IDF** (Term Frequency-Inverse Document Frequency) to convert text into numerical vectors.
- **Spam Filtering:** A practical application using the `SMSSpamCollection` dataset to build a model that distinguishes between "ham" and "spam" messages.

## How it was done
- **Scraping Techniques:** Utilizes Python's power to parse DOM structures and handle web requests.
- **NLP Pipeline:** Each notebook follows a systematic approach:
  1.  **Cleaning:** Removing noise, special characters, and numbers.
  2.  **Normalization:** Reducing words to their root forms (Stemming/Lemmatization).
  3.  **Vectorization:** Applying mathematical models to represent text data.
  4.  **Modeling:** (In the case of spam filter) Training a classifier to recognize patterns in the text.

## Why it was done
- To develop a reusable library of scraping and text processing scripts.
- To document the learning path through various NLP techniques.
- To bridge the gap between unstructured web data and structured machine learning inputs.

## Tech Stack
- **Language:** Python
- **Web Scraping:** Beautiful Soup, Requests (implied)
- **NLP Libraries:** NLTK (Natural Language Toolkit), Scikit-learn
- **Data Science:** Pandas, NumPy
- **Interactive Development:** Jupyter Notebook

## File Structure
- `web_scrapping/`: Contains scripts for data extraction and weather data analysis.
- `natural_language_processing/`: 
  - `tokenize.ipynb`, `stemming.ipynb`, `lemmatize.ipynb`: Preprocessing foundations.
  - `bag_of_words.ipynb`, `tf-idf.ipynb`: Feature extraction methods.
  - `spam_filter.ipynb`: Complete application for spam detection.
  - `SMSSpamCollection`: The dataset used for training the spam classifier.
