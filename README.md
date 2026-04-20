# 📰 Bangla Fake News Detection

This project compares traditional Machine Learning methods with a BanglaBERT-based deep learning model for detecting fake news in Bangla.

## 📌 Features

* TF-IDF + Logistic Regression & SVM
* BanglaBERT (Transformer-based model)
* 5-Fold Cross Validation
* Performance comparison

## 📊 Results

* Logistic Regression: ~63.5% accuracy
* SVM: ~62.7% accuracy
* BanglaBERT: ~82% test accuracy

## 🧠 Model

We used `csebuetnlp/banglabert` for transfer learning.

## ⚙️ Setup

```bash
pip install -r requirements.txt
```

## ▶️ Run

```bash
python notebooks/banglabert.py
```

## 📁 Dataset

Bangla Fake News Dataset (Mendeley)

## 📄 Report

See full report in `report/` folder.

## 👨‍💻 Authors

* Tanzim Qaiyum
* Aarshi Durriya Raihan
* Anika Tahsin
* Maisha Thasin
