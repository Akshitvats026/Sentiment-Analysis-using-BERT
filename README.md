# 🧠 Sentiment Analysis Using BERT

A Natural Language Processing (NLP) project that uses **BERT (Bidirectional Encoder Representations from Transformers)** to classify movie reviews as **Positive** or **Negative**.

## 📌 Project Overview

This project fine-tunes a pretrained **BERT-base-uncased** model on the **IMDb Movie Reviews dataset** for binary sentiment classification. The model understands the contextual meaning of text and predicts the sentiment of a given review.

## 🚀 Features

* 🤖 BERT-based sentiment classification
* 🎬 IMDb movie review dataset
* 🔤 BERT Tokenization
* 📊 Accuracy, Precision, Recall & F1-Score
* 📈 Confusion Matrix visualization
* ✍️ Custom review sentiment prediction
* ☁️ Google Colab compatible

## 🛠️ Technologies Used

* **Python**
* **BERT**
* **Hugging Face Transformers**
* **PyTorch**
* **Scikit-learn**
* **Pandas & NumPy**
* **Matplotlib & Seaborn**
* **Google Colab**

## 📂 Dataset

The project uses the **IMDb Movie Reviews Dataset**, containing movie reviews labeled as:

* `0` → Negative
* `1` → Positive

The dataset is loaded using the Hugging Face `datasets` library.

## ⚙️ Methodology

```text
IMDb Dataset
     ↓
BERT Tokenization
     ↓
BERT Pretrained Model
     ↓
Fine-Tuning
     ↓
Sentiment Classification
     ↓
Model Evaluation
     ↓
Custom Prediction
```

## 📊 Evaluation Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## 💻 Example

**Input:**

```text
"This movie was absolutely amazing. I loved it!"
```

**Output:**

```text
Sentiment: Positive
```

**Input:**

```text
"The movie was boring and disappointing."
```

**Output:**

```text
Sentiment: Negative
```

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/akshitvats026/sentiment-analysis-bert.git
cd sentiment-analysis-bert
```

### 2. Open Google Colab

Upload/open the notebook:

```text
Sentiment-Analysis-BERT.ipynb
```

### 3. Enable GPU

In Google Colab:

```text
Runtime → Change runtime type → T4 GPU
```

### 4. Run All Cells

Execute the notebook from top to bottom.

## 📁 Project Structure

```text
Sentiment-Analysis-BERT/
│
├── Sentiment_Analysis_BERT.ipynb
├── README.md
└── requirements.txt
```

## 🎯 Objective

The main objective of this project is to demonstrate how **Transformer-based BERT models** can be fine-tuned for sentiment classification and applied to real-world NLP tasks.

## 🔮 Future Scope

* Multilingual sentiment analysis
* Aspect-based sentiment analysis
* Fine-tuning advanced models such as RoBERTa
* Deployment as a web application
* Real-time sentiment prediction

## 👨‍💻 Author

**Akshit Vats**

B.Tech CSE (Artificial Intelligence)
Natural Language Processing Project

---

⭐ **If you found this project useful, consider giving it a star!**
