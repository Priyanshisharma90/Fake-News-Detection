# 📰 Fake News Detection
This project detects fake news articles using Natural Language Processing (NLP) and machine learning (Passive Aggressive Classifier). It analyzes news text with TF-IDF features and predicts whether an article is real or fake.

## 📂 Dataset

* News dataset containing text and labels (REAL/FAKE)
* \~40,000 articles


## 📊 ML Approach

* Data preprocessing with pandas
* Train-test split (80/20)
* Feature extraction with **TfidfVectorizer** (removes stopwords, max\_df=0.7)
* Model: **PassiveAggressiveClassifier**
* Evaluation: Accuracy Score & Confusion Matrix

## 📈 Results

* Accuracy: \~92%
* Confusion Matrix shows balanced classification between REAL and FAKE news

## 🔍 Insights

* TF-IDF vectorization effectively captures text patterns in news articles
* Passive Aggressive Classifier is efficient for large sparse datasets
* Helps in building lightweight real-time fake news detectors
