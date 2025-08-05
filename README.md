# Fake_News_Prediction

# 📰 Fake News Detection – Machine Learning Project

## 📌 Overview
Fake news detection is a key Natural Language Processing (NLP) problem that aims to classify news articles as **real** or **fake**.  
This project builds a machine learning pipeline to detect fake news using text data and predictive models.

---

## 📂 Project Workflow

1. **Data Collection**
   - Dataset: [Fake News Dataset](https://drive.google.com/file/d/1vLUzI1dBgNIQAiU5NfuG4UqV8zvfmbKa/view?usp=drive_link)
   - Columns include: `title`, `text`, `label` (1 = Fake, 0 = Real)

2. **Data Preprocessing**
   - Cleaned text (lowercasing, removing punctuation & stopwords)
   - Tokenization & Lemmatization
   - TF-IDF Vectorization for feature extraction

3. **Modeling**
   - Implemented and compared:
     - Logistic Regression
     - Naive Bayes
     - Passive Aggressive Classifier
   - Evaluated with Accuracy, Precision, Recall, and F1‑Score

4. **Results**
   - Logistic Regression: 94% accuracy
   - Naive Bayes: 92% accuracy
   - Passive Aggressive: 93% accuracy
   - Confusion matrix and F1 score visualized

---

## 📊 Visualizations
- WordCloud of most common fake vs real words
- Confusion matrices for model performance
