# Twitter Sentiment Analysis using Machine Learning

This project analyzes the sentiment of tweets (positive, negative, or neutral) using Natural Language Processing (NLP) and traditional machine learning models.

---

## 📊 Overview

- Cleaned and preprocessed tweet data: lowercase conversion, stopword removal, punctuation stripping, and stemming.
- Converted text to numerical features using TF-IDF vectorization.
- Trained multiple classifiers and evaluated their performance.

---

## 🧪 Models Used

- Multinomial Naive Bayes
- Logistic Regression
- Random Forest (optional)
- SVM (optional)

**✅ Accuracy_Score:**  
Achieved an accuracy of **94.88%** using **Multinomial Naive Bayes** with TF-IDF features.

---

## 🚀 How to Run

```bash
git clone https://github.com/Mohit-Nagraj/Twitter_sentimental.git
cd Twitter_sentimental
pip install -r requirements.txt
python app.py  # if using Flask app
