# Naive Bayes for Tweet Sentiment Analysis

This project applies **Naive Bayes** to sentiment analysis on tweets, classifying text as positive or negative using word-frequency statistics and conditional probabilities.

Completed as **Assignment 2** of the *Classification and Vector Spaces in NLP* course, this project explores probabilistic text classification, sentiment prediction, word-count ratios, model evaluation, and error analysis.

---

## 📌 Project Overview

Sentiment analysis is a Natural Language Processing (NLP) task that identifies the emotional polarity expressed in text.

In this assignment, a Naive Bayes model learns from labeled tweets and predicts whether a tweet expresses positive or negative sentiment. The implementation uses the relationship between word occurrences and sentiment classes to calculate a prediction.

---

## 🎯 Objectives

* Train a Naive Bayes model for tweet sentiment classification.
* Test the trained model on labeled data.
* Calculate positive-to-negative word-count ratios.
* Identify words associated with positive or negative sentiment.
* Analyze classification errors.
* Predict the sentiment of a custom tweet.

---

## 📂 Dataset

The assignment uses a labeled tweet dataset for binary sentiment classification.

| Property      | Description           |
| ------------- | --------------------- |
| Data type     | Tweets / text         |
| Task          | Sentiment analysis    |
| Classes       | Positive and negative |
| Learning type | Supervised learning   |
| Input         | Tweet text            |
| Output        | Sentiment label       |

---

## ⚙️ Methodology

### 1. Data Processing

Prepare the tweet data and implement helper functions to count words and organize information according to sentiment labels.

### 2. Naive Bayes Training

Train the classifier using word counts and class-specific probabilities.

The model uses the ratio between positive and negative sentiment probabilities to help determine the predicted class.

### 3. Sentiment Prediction

Implement a prediction function that calculates a sentiment score for a tweet and classifies it as positive or negative.

### 4. Model Evaluation

Test the trained model on the provided test dataset and measure its classification performance.

### 5. Word-Ratio Analysis

Calculate the ratio of positive to negative counts for individual words. Apply thresholds to identify words more strongly associated with either sentiment.

### 6. Error Analysis

Inspect misclassified tweets to understand where the model struggles, including cases involving context, negation, or words that appear in both sentiment classes.

### 7. Custom Tweet Prediction

Use the trained model to predict the sentiment of a user-provided tweet.

---

## 🔄 Workflow

```text
Labeled Tweet Dataset
        ↓
Data Processing
        ↓
Count Words by Sentiment
        ↓
Train Naive Bayes Model
        ↓
Calculate Conditional Probabilities
        ↓
Predict Tweet Sentiment
        ↓
Evaluate on Test Data
        ↓
Analyze Positive/Negative Word Ratios
        ↓
Error Analysis
        ↓
Predict Custom Tweet
```

---

## 🧠 Key Concepts

* Naive Bayes Classifier
* Bayes' Theorem
* Conditional Probability
* Conditional Independence Assumption
* Sentiment Analysis
* Natural Language Processing (NLP)
* Word Frequency Counts
* Positive and Negative Sentiment
* Log Probability Ratios
* Binary Classification
* Model Evaluation
* Error Analysis

---

## 🛠️ Technologies & Tools

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Natural Language Processing utilities

---

## 📈 Learning Outcomes

By completing this assignment, I practiced:

* Applying probabilistic machine learning to text classification.
* Training a Naive Bayes sentiment classifier.
* Using word counts and conditional probabilities for prediction.
* Analyzing positive-to-negative word ratios.
* Evaluating model predictions on test data.
* Investigating errors in sentiment classification.
* Applying a trained model to custom text inputs.

---

## 📁 Notebook

`Naive_Bayes_Tweet_Sentiment_Analysis.ipynb`

The notebook contains data processing, model training, prediction, evaluation, word-ratio analysis, and error-analysis exercises.

---

## 📚 Course Information

| Field         | Details                                 |
| ------------- | --------------------------------------- |
| Course        | Classification and Vector Spaces in NLP |
| Assignment    | Assignment 2 — Naive Bayes              |
| Task          | Tweet Sentiment Analysis                |
| Model         | Naive Bayes                             |
| Learning type | Supervised Learning                     |
| Environment   | Jupyter Notebook                        |

---

## 👨‍💻 Purpose

This project is part of my NLP and machine learning portfolio, demonstrating practical understanding of probabilistic classification, sentiment analysis, and text-based machine learning.
