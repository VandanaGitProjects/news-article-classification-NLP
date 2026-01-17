# News Article Classification (NLP Project)

## 📌 Overview
This project builds a machine learning system to automatically classify news articles into categories such as **politics, sports, wellness, entertainment, and business**. The goal is to demonstrate text preprocessing, feature extraction, and classification model development for real-world NLP tasks.

## 🎯 Problem Statement
In today’s digital landscape, thousands of news articles are published daily. Manually categorizing them is inefficient. This project develops NLP models to classify articles automatically, improving content organization and recommendation systems.

## ⚙️ Project Workflow
1. **Data Exploration & Cleaning**
   - Removed duplicates and handled missing values.
   - Standardized text (lowercasing, punctuation removal, stopword removal).
2. **Text Preprocessing**
   - Tokenization, Lemmatization, and Stemming.
   - Combined headline, description, and keywords into a single text field.
3. **Feature Engineering**
   - TF‑IDF Vectorization (max_features=2000, n‑grams).  
   - Word2Vec embeddings (vector_size=100).  
   - Text length and frequency analysis.
4. **Model Development**
   - Logistic Regression  
   - Naive Bayes (MultinomialNB)  
   - Support Vector Machine (LinearSVC)
5. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1 Score.  
   - Confusion Matrix visualization.  
   - Category distribution and text length analysis.

## 🛠️ Tech Stack
- **Languages & Libraries:** Python, Pandas, NumPy, Scikit‑Learn, NLTK, Matplotlib, Seaborn, Gensim (Word2Vec)
- **Tools:** Jupyter Notebook / Google Colab

## 📊 Results
- **Logistic Regression:** Accuracy ≈ 76% (balanced performance across categories).  
- **Naive Bayes:** Accuracy ≈ 74% (strong for some categories, weaker for others).  
- **SVM (LinearSVC):** Accuracy ≈ 77% (best overall performance).  

## 📂 Repository Structure
