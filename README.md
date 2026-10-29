# Quora Duplicate Question Detection

An end-to-end Natural Language Processing (NLP) pipeline that predicts whether two questions on Quora have the same intent.

## 📌 Features & Architecture
- **Data Preprocessing**: Lowercasing, contraction expansion, special character normalization, and punctuation removal.
- **Basic Feature Engineering**: Character length differences, word counts, common words, and word share ratios.
- **Advanced Token Features**: Min/Max ratios of stop words, token similarity, and first/last word matching.
- **Fuzzy Matching**: FuzzyWuzzy ratios (QRatio, Partial Ratio, Token Sort & Token Set Ratios).
- **Vectorization**: Bag-of-Words (CountVectorizer).
- **Machine Learning Models**: Random Forest Classifier and XGBoost Classifier.

## 📊 Dataset
Dataset sourced from Kaggle: [Quora Question Pairs](https://www.kaggle.com/c/quora-question-pairs).

## 🛠️ Setup & Installation
```bash
git clone [https://github.com/Arif1412/quora-duplicate-question-detection.git](https://github.com/Arif1412/quora-duplicate-question-detection.git)
cd quora-duplicate-question-detection
pip install -r requirements.txt
