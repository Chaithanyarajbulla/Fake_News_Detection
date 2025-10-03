# Fake News Detection Using Machine Learning

A Machine Learning project to classify news articles as **FAKE** or **REAL** using Python, scikit-learn, and NLP techniques. This project includes data preprocessing, feature extraction with TF-IDF, model training, evaluation, and visualization with word clouds.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)  
- [Dataset](#dataset)  
- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Model Evaluation](#model-evaluation)  
- [Visualizations](#visualizations)  
- [Contributing](#contributing)  
- [License](#license)

---

## 📰 Project Overview

Fake news has become a major problem in today's digital age. This project leverages Machine Learning to detect fake news by analyzing the text content. The pipeline includes:

1. Data loading and cleaning  
2. Feature extraction using TF-IDF  
3. Logistic Regression model training  
4. Model evaluation (accuracy, confusion matrix, classification report)  
5. Word cloud visualizations for FAKE vs REAL news  
6. Predicting new news articles

---

## 📂 Dataset

This project uses the **Fake and Real News Dataset** from Kaggle:

- [Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)  

The dataset contains two CSV files:

- `Fake.csv` → FAKE news articles  
- `True.csv` → REAL news articles  

Each file contains columns: `title`, `text`, `subject`, `date`.  

---

## ✨ Features

- **title + text** → Combined as the main text feature  
- **label** → FAKE (0) or REAL (1)  
- **text_length** → Number of characters in each news article  

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection
