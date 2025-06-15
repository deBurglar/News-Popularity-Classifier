# 📰 News Popularity Classifier

A simple machine learning project that predicts whether a news article will be popular based on:
- Headline length
- Description length
- Source

## 📦 Dataset

Fetched live using the [NewsAPI.org](https://newsapi.org) — processed into a structured format with:
- `headline_len`
- `desc_len`
- `source_name`
- `is_popular` (engineered label)

## 📊 Model

Trained a **Logistic Regression classifier** with 3 features:

| Metric     | Value |
|------------|--------|
| Accuracy   | 90%    |
| Precision  | 83%    |
| Recall     | 83%    |
| F1-Score   | 83%    |

## 🔍 Features Used
- `headline_len` — length of the news headline
- `desc_len` — length of the news description
- `source_name` — converted using one-hot encoding

## 📁 Files
- `main.ipynb` — Jupyter notebook with full workflow
- `requirements.txt` — list of required Python libraries

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook


