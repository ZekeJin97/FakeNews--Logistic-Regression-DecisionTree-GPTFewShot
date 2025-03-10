# 📰 Fake News Detection System
This project implements a Fake News Detection System using Logistic Regression, Decision Tree, and a GPT Few-Shot Learning approach. The system classifies news articles as real or fake based on textual content, leveraging TF-IDF vectorization and pretrained language models.

🚀 Key Features
✔ Preprocessing Pipeline:

Tokenization, stopword removal, stemming
TF-IDF vectorization for feature extraction

✔ Machine Learning Models:
Logistic Regression and Decision Tree trained on labeled news datasets
Achieves 98.8% accuracy on test data

✔ GPT Few-Shot Learning Approach:
Utilizes a small set of labeled examples to prompt a GPT-based model for classification
Evaluates model performance against traditional classifiers

✔ Performance Metrics:
Model evaluation using Precision, Recall, F1-score

📊 Dataset
The model is trained on a dataset of real and fake news articles, preprocessed and vectorized for ML models, while GPT-based evaluation is conducted using raw text inputs.

📈 Results
Traditional ML models (Logistic Regression & Decision Tree) achieve 98.8% accuracy with TF-IDF features.
GPT Few-Shot Learning shows promising classification ability with minimal labeled data.
