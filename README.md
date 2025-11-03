# 🧠 Reddit Predictive Sentiment Analysis

## 📄 Overview
This Jupyter notebook performs **sentiment analysis on Reddit comments** related to fast food brands.  
It compares two popular NLP tools — **VADER** and **TextBlob** — to determine which performs better in identifying sentiment polarity in user-generated Reddit text.

---

## 🚀 Features
- **Data Loading & Cleaning**
  - Reads Reddit comment data from a CSV file (`reddit_fastfood_data.csv`).
  - Removes unwanted characters, URLs, emojis, and non-ASCII symbols.
  - Applies tokenization, stopword removal, and lemmatization using NLTK.

- **Sentiment Analysis**
  - Uses **VADER Sentiment Analyzer** (suitable for social media text).
  - Uses **TextBlob Sentiment Analyzer**.
  - Compares polarity and subjectivity between both models.

- **Visualization**
  - Visualizes sentiment distributions and brand comparisons using matplotlib and seaborn.

- **Result Interpretation**
  - Evaluates which sentiment tool produces more reliable and intuitive scores for informal Reddit text.

---

## 🧰 Requirements
Install all required dependencies using:

```bash
pip install pandas numpy nltk textblob matplotlib seaborn
