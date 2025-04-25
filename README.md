# 🎬 Sentiment Analysis on IMDb Movie Reviews

This project applies Natural Language Processing (NLP) to classify movie reviews as **positive** or **negative** using the IMDb dataset. Two classic models — **Logistic Regression** and **Naive Bayes** — are trained and evaluated.

---

## 📊 Dataset Overview

- **Source**: [IMDb 50K Movie Reviews Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Size**: 50,000 reviews (25k positive, 25k negative)
- **Columns**:
  - `review`: Raw text of the review
  - `sentiment`: "positive" or "negative"

---

## 🧼 Text Preprocessing

- Removed HTML tags (e.g., `<br />`)
- Lowercased all words
- Removed punctuation and numbers
- Removed stop words (e.g., "the", "and", "is")
- Final text vectorized using **TF-IDF** (Top 5000 features)

---

## 🤖 Models Trained

### 🔹 Logistic Regression
- **Accuracy**: 88.7%
- **Confusion Matrix**:


### 🔸 Naive Bayes
- **Accuracy**: 85.0%
- **Confusion Matrix**:


### 🧠 Observations
- Logistic Regression outperformed Naive Bayes
- Lower false positives/negatives
- Better overall F1-score and recall

---

## 📈 Model Comparison

![Confusion Matrix Comparison](sentiment_model_comparison.png)

---

## 🧰 Libraries Used

- Python, Pandas, NumPy
- Scikit-learn: `TfidfVectorizer`, `LogisticRegression`, `MultinomialNB`, `LabelEncoder`
- NLTK for stopword removal
- Seaborn & Matplotlib for plotting

---

## 🏁 Project Status

✅ Completed  
🧠 Models Evaluated  
📊 Visualized  
📁 GitHub-Ready

---

## ✨ Author

**Lokesh Mandarapu**  
[LinkedIn](https://linkedin.com/in/mandarapulokesh)
