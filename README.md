# 🎬 IMDB Movie Review Sentiment Analysis (RNN & LSTM)

## 📌 Project Overview

This project focuses on building a **Deep Learning model** to classify movie review sentiments (**Positive vs Negative**) using the IMDB dataset.
It demonstrates a complete **Natural Language Processing (NLP) pipeline**, from text preprocessing to training a Recurrent Neural Network (RNN/LSTM) using PyTorch.

---

## 🚀 Key Performance Metrics

* **Accuracy:** 85.89% on test dataset
* **Dataset Size:** 50,000 movie reviews
* **Training Performance:** Reduced training loss to ~0.09 over 10 epochs

---
## 📊 Data Source
The dataset used in this project is the **IMDB Dataset of 50K Movie Reviews**.
* **Source:** [Kaggle - IMDB Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
* **Note:** The full 64 MB dataset is excluded from this repository to optimize performance.

---

## 🛠️ Technical Stack

* **Language:** Python
* **Deep Learning:** PyTorch
* **NLP:** NLTK (Tokenization, Stopwords, PorterStemmer)
* **Data Tools:** Pandas, Scikit-learn (TF-IDF, Label Encoding)

---

## 💡 Implementation Workflow

### 🔹 1. Text Preprocessing

* Converted text to lowercase
* Removed HTML tags, URLs, and punctuation using Regex
* Removed stopwords and applied stemming

### 🔹 2. Feature Engineering

* Encoded sentiment labels into binary format
* Converted text into numerical features using **TF-IDF (5000 features)**

### 🔹 3. Deep Learning Model

* Implemented **RNN and LSTM architectures**
* Hidden layer size: 128
* Batch size: 64 (using DataLoader)
* Loss Function: BCELoss
* Optimizer: Adam

---

## 📂 Project Structure

```
/notebooks
   └── IMDB_rating_RNN.ipynb
/data
   └── IMDB Dataset (50K reviews)
/README.md
```

## 📊 Results

The model successfully classifies sentiment with **85.89% accuracy**, demonstrating strong capability in handling **sequential text data using deep learning**.

---

## 📬 Contact

📧 [utkarshbachhav08@gmail.com](mailto:utkarshbachhav08@gmail.com)
🔗 LinkedIn: [www.linkedin.com/in/utkarsh-bachhav-24240b27b] 
