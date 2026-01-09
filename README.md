# 📰 Fake News Detection using NLP and TF-IDF

## 📌 Project Overview
This project focuses on detecting **fake and real news articles** using **Natural Language Processing (NLP)** techniques and **Machine Learning**. The objective is to classify news content by analyzing textual patterns and word importance using **TF-IDF vectorization** combined with **Logistic Regression**.

Fake news detection is a critical real-world application of NLP in media, journalism, and social platforms.

---

## 🧠 Problem Type
- Binary Text Classification
- Classes: Fake News / Real News
- Data Type: Unstructured text data

---

## 🔄 NLP Preprocessing Steps
The following preprocessing techniques are applied:
- Removal of special characters and punctuation using Regular Expressions
- Conversion to lowercase
- Tokenization
- Stopword removal
- Text normalization

---

## 🧪 Feature Engineering
### 🔹 TF-IDF Vectorization
- Converts text into numerical features
- Assigns importance to words based on frequency and rarity
- Reduces impact of common words

---

## 🤖 Machine Learning Model
### Logistic Regression
- Linear classification algorithm
- Works efficiently with high-dimensional sparse data
- Commonly used baseline model for NLP tasks

---

## 📊 Model Evaluation
- Train-Test Split: 80% / 20%
- Evaluation Metrics:
  - Accuracy Score

---

## 🛠️ Libraries Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- re (Regular Expressions)

---

## ▶️ How to Run the Project

```bash
pip install -r requirements.txt
python src/fake_news_detection.py

# Fake-News-Detection
