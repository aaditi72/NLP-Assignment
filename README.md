# 📰 News Article Text Classification using NLP

## 📌 Overview

This project focuses on automatically classifying news articles into predefined categories such as **World, Sports, Business, and Sci/Tech** using Natural Language Processing (NLP) techniques.

The project demonstrates how machine learning models can effectively handle high-dimensional textual data and perform accurate text classification.

---

## 🎯 Objective

* Classify news articles into multiple categories
* Apply NLP techniques for preprocessing and feature extraction
* Compare performance of different machine learning models

---

## 🛠️ Tech Stack

* Python
* Google Colab
* Scikit-learn
* Pandas, NumPy
* NLP (TF-IDF Vectorization)

---

## 📂 Dataset

* **AG News Dataset**
* Contains news articles categorized into:

  * World
  * Sports
  * Business
  * Sci/Tech

---

## ⚙️ Methodology

1. **Data Loading**

   * Load AG News dataset

2. **Text Preprocessing**

   * Lowercasing
   * Removing noise and unwanted characters

3. **Feature Extraction**

   * TF-IDF (Term Frequency – Inverse Document Frequency)

4. **Model Training**

   * Naive Bayes
   * Logistic Regression
   * Support Vector Machine (SVM)

5. **Evaluation**

   * Accuracy
   * F1 Score

---

## 📊 Results

| Model               | Accuracy   | F1 Score   |
| ------------------- | ---------- | ---------- |
| Naive Bayes         | 90.70%     | 0.9066     |
| Logistic Regression | 92.13%     | 0.9212     |
| SVM (LinearSVC)     | **92.21%** | **0.9219** |

---

## 🔍 Key Insights

* SVM achieved the best performance
* TF-IDF helped convert text into meaningful numerical features
* Bigrams improved contextual understanding
* Some overlap exists between Business and World categories

---

## 🧠 Conclusion

Traditional machine learning models combined with TF-IDF can achieve high accuracy in text classification tasks.
Among all models, **SVM proved to be the most effective**.

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Upload the dataset (if required)
3. Run all cells
4. View results and model performance

---

## 📁 Project Structure

```
nlp-news-classification/
│── NLP_Code.ipynb
│── README.md
```

---

## 🔮 Future Improvements

* Implement Deep Learning models (LSTM, BERT)
* Improve classification of overlapping categories
* Deploy as a web application


---

## ⭐ Acknowledgement

This project was developed as part of academic learning to explore NLP and machine learning techniques for text classification.

