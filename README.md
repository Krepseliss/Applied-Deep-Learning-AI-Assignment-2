# 📰 Fake News Detection using DistilBERT
🚀 **Binary Classification of Fake and Real News using Transformer Models**

## 📌 Project Overview
This project uses a **DistilBERT** transformer model to classify news articles as **real or fake**. The dataset is sourced from Kaggle and consists of labeled news articles. The model achieves high accuracy in detecting misinformation.

---

## 📂 Dataset
- **Source:** [Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- **Structure:**
  - `True.csv` → Real news articles
  - `Fake.csv` → Fake news articles
- **Preprocessing:**
  - Combined `title` and `text` columns for better context.
  - Added labels (`1` = Real, `0` = Fake).
  - Tokenized text using **DistilBERT Tokenizer**.

---

## ⚙️ Installation
Clone this repository and install dependencies:
```bash
git clone https://github.com/your_username/fake-news-detection.git
Open Powershell in windows and run:
pip install -r "path/to/requirements.txt"
