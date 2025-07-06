
# 📰 Fake News Prediction using NLP

## 🔍 Problem Statement
The spread of fake news on the internet, especially on social media platforms, has become a major concern. This project aims to build a machine learning model that can classify news articles as **Real** or **Fake** using **Natural Language Processing (NLP)** techniques.

## ✅ Objectives
- Preprocess and clean the news data.
- Extract meaningful features using TF-IDF vectorization.
- Train a classification model using Logistic Regression.
- Evaluate the model’s performance on unseen news articles.

## 🛠️ Tech Stack
- Python
- Google Colab
- NLTK (Natural Language Toolkit)
- Scikit-learn
- Pandas, NumPy, Matplotlib

## 📁 Dataset
The dataset contains labeled news articles with the following structure:

| Column | Description |
|--------|-------------|
| `title` | Headline of the article |
| `text`  | Full text content of the article |
| `label` | Target variable (0 = Real, 1 = Fake) |

> 📌 You can upload the dataset directly into Colab using:
```python
from google.colab import files
uploaded = files.upload()
```

## 🔄 Workflow

1. **Data Preprocessing**
   - Lowercasing
   - Removing punctuation
   - Removing stopwords
   - Lemmatization

2. **Feature Extraction**
   - Tokenization
   - TF-IDF vectorization

3. **Model Building**
   - Train-test split
   - Logistic Regression classifier

4. **Evaluation**
   - Accuracy score
   - Confusion matrix (optional)

## 🚀 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Upload the dataset using `files.upload()`.
3. Run all the cells sequentially.
4. View the model’s prediction and accuracy results.

## 📊 Result
The Logistic Regression model achieved a high accuracy score on the validation set, showing effective classification between real and fake news articles.

## 🔒 Future Improvements
- Use deep learning models like LSTM or BERT for better accuracy.
- Include metadata like source, author, and publication date.
- Create a web interface for real-time predictions.

## 👩‍💻 Author
**Safrin M**  
AI & Data Science Student
