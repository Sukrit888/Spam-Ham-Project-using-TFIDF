
# 📩 Spam vs. Ham Classifier using TF-IDF (Google Colab)

This machine learning project classifies SMS messages as **Spam** or **Ham (Not Spam)** using **TF-IDF vectorization** and models like **Logistic Regression** and **Multinomial Naive Bayes**. Built and executed in **Google Colab**, this project demonstrates an end-to-end NLP pipeline for binary text classification.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Libraries Used](#libraries-used)
- [Project Workflow](#project-workflow)
- [Model Performance](#model-performance)
- [How to Run](#how-to-run)
- [License](#license)

---

## 🧠 Overview

The goal of this project is to automate spam detection in SMS messages using natural language processing and machine learning. After preprocessing the text, **TF-IDF** is used to extract features, which are then fed into classifiers to predict message categories.

---

## 📊 Dataset

- **Name:** SMS Spam Collection Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)
- **Size:** 5,574 messages
- **Labels:**  
  - `ham`: Normal message  
  - `spam`: Unwanted/spam message

---

## 🧰 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `nltk`
- `sklearn`

---

## 🔄 Project Workflow

1. **Data Import & Cleaning**
   - Read dataset
   - Remove duplicates
   - Add message length feature

2. **Exploratory Data Analysis**
   - Count plot of spam vs. ham
   - Distribution of message lengths

3. **Text Preprocessing**
   - Lowercasing
   - Removing punctuation and stopwords
   - Tokenization & stemming (using NLTK)

4. **Feature Engineering**
   - TF-IDF Vectorization

5. **Model Building**
   - Train-test split
   - Train using **Multinomial Naive Bayes** and **Logistic Regression**

6. **Evaluation**
   - Accuracy
   - Confusion Matrix
   - Classification Report

---

## 📈 Model Performance

| Model                    | Accuracy | Notes                        |
|-------------------------|----------|------------------------------|
| Logistic Regression     | ~96.4%   | Performs well with TF-IDF    |
| Multinomial Naive Bayes | ~95.7%   | Slightly faster, still robust |

---

## ▶️ How to Run

You can run this project directly on **Google Colab**:

📎 **[Open in Google Colab](https://colab.research.google.com/drive/1cUKxw3qO0foOzoRtl1C87YOcYH13yMsu?usp=sharing)**  

### Steps:
1. Click on the Colab link.
2. Select **“Runtime > Run all”**.
3. No installation is required; it will run entirely in the cloud.

---

---

## 🪪 License

This project is licensed under the **MIT License**. Feel free to use and modify it.
