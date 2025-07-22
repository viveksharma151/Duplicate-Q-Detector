# 🔁 Duplicate Question Pair Detection

This project identifies whether two questions are **duplicates** or **semantically similar** using machine learning. Inspired by platforms like **Quora**, it helps detect if two questions essentially mean the same thing, despite different wording.

The model is built using a **Random Forest Classifier** and a variety of **textual similarity features** to determine duplication. It’s ideal for NLP beginners and those exploring semantic similarity tasks.

---

## 🧠 Overview

On platforms like Quora or Stack Overflow, users often ask the same question using slightly different phrasing. This project solves that by determining whether a pair of questions are **duplicates** using a trained machine learning model.

The solution uses:
- Text preprocessing and feature extraction
- Supervised learning with Random Forest
- Evaluation using real-world Quora question pair dataset

---

## 🔧 Tech Stack

- **Python**
- **Pandas / NumPy**
- **Scikit-learn**
- **NLTK** (for text preprocessing)
- **Random Forest Classifier**
- **Jupyter Notebook** (for experimentation)
- (Optional) **Streamlit or Flask** for UI

---

## ✨ Features Used

The model uses engineered features that quantify how similar two questions are, including:

- Word overlap ratio
- TF-IDF cosine similarity
- Common word count
- Length difference
- Fuzzy string matching scores
- Levenshtein distance
- Token and character-level features

---

## 🧪 Model Overview

• **Random Forest Classifier** — chosen for its strong performance on structured data and ability to capture non-linear relationships.

• Compared with other models like:
  - Logistic Regression
  - SVM
  - XGBoost  
  Random Forest offered the best trade-off between **accuracy**, **robustness**, and **interpretability**.

---



