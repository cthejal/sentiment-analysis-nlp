# Sentiment Analysis using NLP & Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square)
![NLP](https://img.shields.io/badge/NLP-NLTK-green?style=flat-square)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Classification-orange?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)

> NLP pipeline that classifies text as positive, negative, or neutral — using TF-IDF feature extraction and machine learning models trained on labeled review data.

---

## Problem Statement

Businesses receive thousands of customer reviews daily but lack the capacity to read them all manually. This project automates sentiment classification using NLP — enabling teams to quickly understand customer opinion at scale and prioritize responses.

---

## Results

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---|---|---|---|
| Logistic Regression | — | — | — | — |
| Naive Bayes | — | — | — | — |

> Fill in your actual scores from the notebook output.

---

## Features

- Full text preprocessing pipeline: cleaning, tokenization, stopword removal, lemmatization
- Feature extraction using TF-IDF vectorization
- Model training and comparison: Logistic Regression, Naive Bayes
- Evaluation using accuracy, precision, recall, F1-score, and confusion matrix
- Sentiment distribution visualization
- Prediction on custom input text

---

## Tech Stack

| Category | Tools |
|---|---|
| Language | Python 3.x |
| NLP | NLTK (tokenization, stopwords, lemmatization) |
| Feature Extraction | TF-IDF (Scikit-learn) |
| Machine Learning | Scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook / Google Colab |

---

## Dataset

- **File:** `sentiment_reviews_task4.csv`
- **Structure:** Text column + label column (positive / negative / neutral)
- Compatible with any labeled sentiment dataset (movie reviews, tweets, product reviews)

---

## Project Structure

```
sentiment-analysis-nlp/
│
├── sentiment_analysis_task4.ipynb    # Main notebook
├── sentiment_reviews_task4.csv       # Dataset
└── README.md
```

---

## How to Run

```bash
# 1. Clone the repo
git clone https://github.com/cthejal/sentiment-analysis-nlp.git
cd sentiment-analysis-nlp

# 2. Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn nltk

# 3. Download NLTK data (run once)
python -c "import nltk; nltk.download('stopwords'); nltk.download('wordnet')"

# 4. Open the notebook
jupyter notebook sentiment_analysis_task4.ipynb
```

---

## Key Learnings

- Building an end-to-end NLP preprocessing pipeline
- Understanding TF-IDF vectorization and its advantages over Bag of Words
- Comparing classification models on text data using standard evaluation metrics
- Interpreting confusion matrices for multi-class sentiment problems

---

## Future Improvements

- [ ] Add deep learning model (LSTM or BERT) for improved accuracy
- [ ] Build a Streamlit app for real-time sentiment prediction on user input
- [ ] Expand to aspect-based sentiment analysis
- [ ] Train on a larger, domain-specific dataset (e.g., Twitter API data)

---

## Author

**Thejal C Kotian**
[LinkedIn](https://linkedin.com/in/thejalckotian2003) · [GitHub](https://github.com/cthejal) · thejalck@gmail.com
