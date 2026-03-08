# Naïve Bayes Sentiment Analysis (NLP Project)

This project implements a **Sentiment Analysis model** using the **Naïve Bayes algorithm** in Natural Language Processing (NLP).  
The model classifies text reviews as **positive** or **negative** based on the words in the review.

---

## Project Overview

Sentiment analysis is a common task in NLP that aims to determine the emotional tone behind a piece of text.  
In this project we apply the **Multinomial Naïve Bayes classifier** to classify movie reviews.

The workflow includes:

1. Data collection
2. Text preprocessing
3. Feature extraction using Bag of Words
4. Training a Naïve Bayes model
5. Model evaluation

---

## Project Structure


naive-bayes-sentiment-analysis
│
├── data
│ └── movie_reviews.csv
│
├── results
│ └── confusion_matrix.png
│
├── src
│
├── naive_bayes_sentiment.ipynb
│
├── requirements.txt
│
└── README.md


---

## Technologies Used

- Python
- Google Colab
- Scikit-learn
- NLTK
- Pandas
- NumPy
- Matplotlib
- Seaborn



## Installation

Clone the repository:


git clone https://github.com/Doaa-ali790/naive-bayes-sentiment-analysis.git

Go to the project directory:

cd naive-bayes-sentiment-analysis

Install dependencies:

pip install -r requirements.txt
Dataset

The dataset contains movie reviews labeled as:

Positive

Negative

Example:

Text	Sentiment
I love this movie	positive
This movie is terrible	negative
Model Workflow
1. Text Preprocessing

Lowercasing text

Removing punctuation

Removing stopwords

2. Feature Extraction

The text is converted into numerical features using Bag of Words (CountVectorizer).

3. Model Training

We train a Multinomial Naïve Bayes classifier.

4. Model Evaluation

We evaluate the model using:

Accuracy

Confusion Matrix

Example Prediction

Input:

this movie is amazing

Output:

positive
Results

The model predicts whether a review is positive or negative based on the trained dataset.

A confusion matrix is generated to evaluate the performance of the model.

Author

Doaa Ali
