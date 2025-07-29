
# Resume Text Classifier

This project classifies resumes into job categories (e.g., Software Developer, Data Scientist, Marketing) using:

- NLP (spaCy)
- TF-IDF Vectorization
- Logistic Regression / Naive Bayes

## 🚀 Features

- Tokenization, stopword removal, and lemmatization
- TF-IDF vectorization
- Text classification using scikit-learn
- Accuracy score evaluation

## 📦 Requirements

Install dependencies:

```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

## 💻 Usage:
Run the classifier:
```
python resume_classifier.py
```

## 📁 Dataset:
You can modify the sample dataset in resume_classifier.py or place a custom CSV in data/sample_resumes.csv.

## 🔄 Model Options:
 - Logistic Regression (default)
 - Multinomial Naive Bayes (alternative, uncomment in code)
