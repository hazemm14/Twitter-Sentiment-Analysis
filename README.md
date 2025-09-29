# Twitter Sentiment Analysis 🐦📊

This project uses **TensorFlow/Keras** and **LSTM** networks to classify the sentiment of tweets into 3 categories:

* Negative 😡
* Neutral 😐
* Positive 😀

## 📌 Project Overview

* **Dataset**: Small sample of Airline Tweets (5000 tweets) for quick testing.
* **Goal**: Predict the sentiment of a tweet based on its text.
* **Model**: Embedding + LSTM + Dense layers.

## 🛠️ Requirements

* Python 3.x
* TensorFlow
* Pandas
* NumPy
* scikit-learn

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🚀 How to Run

1. Make sure `tweets_sample.csv` is in the project folder.
2. Run the script:

```bash
python sentiment_analysis.py
```

## 📊 Results

* Accuracy varies depending on dataset size (~80% expected).
* Outputs a classification report with Precision, Recall, and F1-score.

## 📂 Project Structure

```
twitter-sentiment-analysis/
│── sentiment_analysis.py
│── requirements.txt
│── README.md
│── tweets_sample.csv
```

## 🔮 Future Work

* Use full Airline Tweets dataset or Sentiment140 for better accuracy.
* Try pre-trained embeddings (GloVe, Word2Vec) or transformer models (BERT).
