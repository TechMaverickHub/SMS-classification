# SMS Spam Classification

A machine learning project to classify SMS messages as **spam** or **ham** (not spam) using Natural Language Processing (NLP) techniques.

## 📁 Project Structure

- `spam.csv`: Dataset containing SMS messages labeled as spam or ham.
- `sms-classification-notebook.ipynb`: Jupyter Notebook for preprocessing, training, evaluating, and visualizing the SMS classifier.

## 📊 Dataset

The dataset consists of SMS messages with the following columns:

- `label`: Indicates whether the message is spam or ham.
- `message`: The content of the SMS message.

> Dataset source: Originally from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection).

## 🧠 Models Used

The following models were explored:

- Naive Bayes (MultinomialNB)
- Support Vector Machine (SVM)
- Logistic Regression

## 🧪 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## 🛠️ Features and Techniques

- Text preprocessing: Lowercasing, stopword removal, punctuation removal, stemming
- TF-IDF Vectorization
- Train/test split
- Model evaluation and comparison
