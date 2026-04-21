# ⭐ Yelp Sentiment Analysis with Deep Learning

This project performs sentiment analysis on Yelp reviews using natural language processing (NLP) and deep learning techniques.

---

## 📊 Project Overview

Understanding customer sentiment is essential for businesses. In this project, we analyze Yelp reviews and classify them as **positive** or **negative** using a deep learning model.

To simplify the problem, we focus on extreme ratings:
- 1-star reviews → Negative (0)
- 5-star reviews → Positive (1)

---

## 📁 Dataset

The dataset contains Yelp user reviews and ratings.

- Text reviews (input)
- Star ratings (target)

Preprocessing steps:
- Removed neutral reviews (3 stars)
- Converted labels into binary classes (0 and 1)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- TensorFlow / Keras
- Scikit-learn
- NLP (Text Preprocessing)

---

## ⚙️ Workflow

1. Data Cleaning
2. Text Preprocessing
   - Lowercasing
   - Removing punctuation & numbers
   - Tokenization & Lemmatization
3. Text Vectorization
4. Model Building (Deep Learning)
5. Model Training
6. Model Evaluation


Results
Accuracy: ~97.6%
Strong generalization on validation data
Effective classification of positive and negative sentiment

