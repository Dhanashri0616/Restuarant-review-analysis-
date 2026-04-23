# 🍽️ Restaurant Review Analysis (NLP Project)

## 📌 Overview
This project focuses on analyzing restaurant customer reviews using **Natural Language Processing (NLP)** and **Machine Learning** techniques.  
The main objective is to classify reviews as **Positive** or **Negative** based on customer feedback.

This helps businesses understand customer satisfaction, identify common issues, and improve service quality.

---

## 🚀 Features
- Data Cleaning and Text Preprocessing  
- Stopword Removal and Stemming  
- Feature Extraction using **Bag of Words / CountVectorizer**  
- Sentiment Classification using Machine Learning Models  
- Accuracy Evaluation and Model Comparison  
- Predict custom reviews  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- NLTK  
- Scikit-learn  

---

## 📂 Dataset
The dataset contains restaurant customer reviews with labels:

- **1 = Positive Review**
- **0 = Negative Review**

Example:

| Review | Sentiment |
|--------|-----------|
| Food was amazing | 1 |
| Service was very slow | 0 |

---

## 🔄 Project Workflow

### 1️⃣ Import Libraries
Used essential Python libraries for data processing and model building.

### 2️⃣ Data Preprocessing
- Removed punctuation  
- Converted text to lowercase  
- Removed stopwords  
- Applied stemming  

### 3️⃣ Feature Extraction
Converted text into numerical format using:

- CountVectorizer  
- Bag of Words  

### 4️⃣ Model Training
Applied Machine Learning algorithms such as:

- Naive Bayes  
- Logistic Regression  
- Random Forest  

### 5️⃣ Evaluation
Measured model performance using:

- Accuracy Score  
- Confusion Matrix  
- Classification Report  

---

## 📊 Results
Achieved high accuracy in predicting customer sentiment from reviews.

Example Output:

| Review | Prediction |
|--------|------------|
| Great food and nice staff | Positive |
| Worst experience ever | Negative |

---

## 💡 Business Use Cases
- Customer feedback analysis  
- Improve restaurant service  
- Detect unhappy customers  
- Brand reputation monitoring  

---

## ▶️ How to Run Project

```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn
