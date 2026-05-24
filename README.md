# 📰 News Topic Classifier using BERT

A fine-tuned transformer-based NLP model that classifies news headlines into predefined categories using **BERT (bert-base-uncased)**.  
The project includes model training, evaluation, and deployment using **Streamlit + Hugging Face Spaces**.

---

## 🚀 Live Demo
👉https://huggingface.co/spaces/MahboobAli123/news-classifier 

## 📌 Project Objective

The goal of this project is to:
- Fine-tune a pretrained BERT model on the AG News dataset
- Classify news headlines into topic categories
- Evaluate performance using accuracy and F1-score
- Deploy the model using a web interface (Streamlit)

---

## 🧠 Model Details

- Model: `bert-base-uncased`
- Framework: Hugging Face Transformers
- Task: Text Classification
- Dataset: AG News Dataset (Hugging Face Datasets)

---

## 📊 Dataset Information

- **Dataset:** AG News Dataset
- **Classes:**
  - World
  - Sports
  - Business
  - Sci/Tech

- **Samples:**
  - Train: 120,000 samples
  - Test: 7,600 samples

---

## ⚙️ Tech Stack

- Python 🐍
- PyTorch 🔥
- Hugging Face Transformers 🤗
- Hugging Face Datasets
- Streamlit 🎈
- scikit-learn 📊

---

## 🏗️ Project Workflow

1. Load AG News dataset
2. Tokenize text using BERT tokenizer
3. Fine-tune `bert-base-uncased`
4. Train model using Trainer API
5. Evaluate using Accuracy & F1-score
6. Save trained model
7. Deploy using Streamlit app

---

## 📈 Model Performance

- Accuracy: **92%+**
- F1 Score: **0.92+**

---

## 🖥️ How to Run Locally

### 1. Clone repository
```bash
git clone https://github.com/your-username/news-classifier-bert.git
cd news-classifier-bert
