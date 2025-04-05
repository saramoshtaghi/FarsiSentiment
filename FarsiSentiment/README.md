# 🧠 Persian Sentiment Analysis with BERT

This project performs sentiment analysis on Persian (Farsi) text using a pretrained BERT model from Hugging Face.  
It analyzes customer reviews from the Digikala dataset and predicts whether a review is **recommended** or **not recommended**.

---
## 🧠 Author

**Sara Moshtaghi** — NLP Researcher & Machine Learning Engineer  
[LinkedIn](https://linkedin.com/in/saramoshtaghi) | [GitHub](https://github.com/saramoshtaghi)

---

## 📌 Project Overview

- **Language:** Persian (Farsi)
- **Model Used:** [`HooshvareLab/bert-fa-base-uncased-sentiment-digikala`](https://huggingface.co/HooshvareLab/bert-fa-base-uncased-sentiment-digikala)
- **Dataset:** Digikala Product Comments (from Kaggle)
- **Task:** Binary Sentiment Classification  
- **Pipeline:** Hugging Face Transformers

---

## ⚙️ Workflow

1. Load Digikala comments dataset (`Text`, `Suggestion`)
2. Map numeric labels (`1 = recommended`, `0 = not_recommended`)
3. Use pretrained BERT model to predict sentiments on sample reviews
4. Evaluate model using Accuracy and F1-score

---

## 📊 Results

- **Accuracy:** 94%
- **F1 Score:** 97%
- **Sample Size:** 100 random reviews
- **Label Mapping:**
  - `1 → recommended`
  - `0 → not_recommended`

---

## 🔧 Tools & Libraries

- Python 🐍
- [Transformers](https://huggingface.co/docs/transformers/index)
- [scikit-learn](https://scikit-learn.org/)
- pandas, tqdm

---

## 📁 Project Structure

farsi-sentiment-analysis/
├── data/
│   └── digikala_comments.csv
├── notebook/
│   └── digikala_analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore

