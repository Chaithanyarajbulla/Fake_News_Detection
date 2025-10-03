# Fake News Detection Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24-orange?logo=scikitlearn)
![License](https://img.shields.io/badge/License-MIT-green)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1y_N9m-v499kiTFM6xL2lM4skMzvorwds?usp=drive_link)

---

## 📰 Project Overview

This project focuses on detecting **fake news** using **Machine Learning** and **Natural Language Processing (NLP)**. With the rise of misinformation online, automatically classifying news as **FAKE** or **REAL** is crucial.  

The project includes:  

- Data preprocessing and cleaning  
- TF-IDF feature extraction  
- Logistic Regression model training  
- Model evaluation (accuracy, confusion matrix, classification report)  
- Visualizations (word clouds, class distribution, text length distribution)  
- Prediction of new news articles  

---

## 📂 Dataset

We use the **Fake and Real News Dataset** from Kaggle:  

- [Dataset Link](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)  

**Files:**  
- `Fake.csv` → FAKE news articles  
- `True.csv` → REAL news articles  

Columns include: `title`, `text`, `subject`, `date`. We combine `title` and `text` as the main feature for the model.

---

## 🔍 Methodology

### 1. Data Preprocessing
- Remove missing values  
- Combine `title` and `text`  
- Clean text: lowercase, remove special characters, extra spaces  

### 2. Feature Extraction
- TF-IDF Vectorization  
- Stopword removal  

### 3. Model Training
- Logistic Regression classifier  
- Train-test split (80/20)  

### 4. Evaluation
- Accuracy  
- Confusion Matrix  
- Classification Report  

### 5. Visualization
- Class distribution  
- Text length distribution  
- Word clouds for FAKE vs REAL news  

### 6. Prediction
- Predict FAKE/REAL for new articles (single or multiple)

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection
