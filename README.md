# 📩 Smart SMS Spam Detector

An end-to-end Natural Language Processing (NLP) project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using machine learning techniques.

The project demonstrates the complete pipeline from raw text preprocessing to feature extraction and model training. Multiple vectorization approaches such as Bag of Words, TF-IDF, and Word2Vec are explored and compared.

---

## 🚀 Features
- Text cleaning using regex
- Tokenization and normalization
- Stopword removal
- Stemming / Lemmatization
- Feature engineering with:
  - CountVectorizer (Bag of Words)
  - TF-IDF
  - Word2Vec embeddings
- Model training using Naive Bayes
- Conversion of text into numerical vectors for ML

---

## 🧠 Tech Stack
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Gensim

---

## 📂 Dataset
SMS messages labeled as **spam** or **ham**.

---

## ⚙️ Workflow
Raw Text → Cleaning → Tokenization → Stopword Removal → Stemming/Lemmatization → Vectorization → Model Training → Prediction

---

## 🎯 Goal
To understand how machines interpret human language and apply classical NLP techniques to build a real-world spam detection system.

---

## 📌 Future Improvements
- Try advanced models (Logistic Regression, SVM, Neural Networks)
- Use TF-IDF weighted Word2Vec
- Deploy as a web application
- Hyperparameter tuning

