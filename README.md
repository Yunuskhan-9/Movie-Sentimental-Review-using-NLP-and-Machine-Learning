# 🎬 Movie Review Sentiment Analysis

## 📌 Project Overview

With the increasing number of user-generated movie reviews on platforms like IMDb and Rotten Tomatoes, understanding audience sentiment has become essential.

This project uses **Natural Language Processing (NLP)** and **Machine Learning** techniques to classify movie reviews as **Positive** or **Negative** based on their textual content.

---

## 🎯 Problem Statement

To build a machine learning model that accurately classifies movie reviews into:

* ✅ Positive
* ❌ Negative

---

## 📂 Dataset

The dataset contains two columns:

* **Review** → Textual movie review
* **Sentiment** → Label (Positive / Negative)

---

## ⚙️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* NLTK
* Scikit-learn
* BeautifulSoup
* TextBlob

---

## 🔍 Project Workflow

### 1️⃣ Data Exploration

* Checked dataset shape, columns, and structure
* Used `info()`, `describe()`
* Handled missing values and duplicates

---

### 2️⃣ Data Preprocessing

* Removed HTML tags and URLs
* Converted text to lowercase
* Removed special characters
* Tokenization
* Stopwords removal
* Stemming (Porter Stemmer)
* Slang handling (basic)
* Removed extra spaces

---

### 3️⃣ Feature Engineering

* Bag of Words (CountVectorizer)
* TF-IDF (optional improvement)

---

### 4️⃣ Encoding

* Sentiment column encoded using LabelEncoder

---

### 5️⃣ Model Training

Models used:

* Logistic Regression
* Naive Bayes
* Random Forest

---

### 6️⃣ Model Evaluation

Metrics used:

* Accuracy Score
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)

---

## 📊 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~85–90%  |
| Naive Bayes         | ~83–88%  |
| Random Forest       | ~80–85%  |

---

## 🧪 Sample Code

```python
# Prediction
y_pred = model.predict(X_test)

# Evaluation
from sklearn.metrics import accuracy_score
print("Accuracy:", accuracy_score(y_test, y_pred))
```

---

## 🚀 How to Run the Project

```bash
# Clone repository
git clone https://github.com/your-username/movie-sentiment-analysis.git

# Navigate to project
cd movie-sentiment-analysis

# Install dependencies
pip install -r requirements.txt

# Run script
python main.py
```

---

## 📈 Improvements

* Use N-grams
* Hyperparameter tuning
* Deep Learning models (LSTM, BERT)
* Larger dataset

---

## 🔮 Future Scope

* Real-time sentiment analysis
* Web app deployment (Streamlit/Flask)
* Integration with movie platforms

---

## 🧠 Key Learnings

* Text preprocessing is the most important step in NLP
* TF-IDF often performs better than Bag of Words
* Naive Bayes works well for text classification

---

## 📚 References

* NLTK Documentation
* Scikit-learn Documentation
* TextBlob Documentation

---

## 👨‍💻 Author

Your Name

---

⭐ If you like this project, give it a star!
# Movie-Sentimental-Review-using-NLP-and-Machine-Learning
