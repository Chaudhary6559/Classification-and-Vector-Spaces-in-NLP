# Logistic Regression for Tweet Sentiment Analysis

This project implements **Logistic Regression from scratch** to perform sentiment analysis on tweets, classifying them as positive or negative.

Completed as **Assignment 1** of the *Classification and Vector Spaces in NLP* course, the project introduces fundamental machine learning concepts for natural language processing (NLP), including text feature extraction, model training, prediction, and error analysis.

---

## 📌 Project Overview

Sentiment analysis is an NLP task that identifies the emotional polarity expressed in text.

In this project, a logistic regression model learns from labeled tweets and predicts whether a tweet expresses positive or negative sentiment.

The assignment focuses on understanding how logistic regression works mathematically and applying it to a practical text-classification problem.

---

## 🎯 Objectives

* Extract numerical features from text for logistic regression.
* Implement logistic regression from scratch.
* Understand the sigmoid function and its role in binary classification.
* Implement gradient descent to optimize model parameters.
* Train a sentiment classifier using tweet data.
* Make predictions on unseen tweets.
* Evaluate model performance using a test set.
* Perform error analysis to understand incorrect predictions.

---

## 📂 Dataset

The project uses a labeled tweet dataset for binary sentiment classification.

| Property      | Description           |
| ------------- | --------------------- |
| Data type     | Tweets / text         |
| Task          | Sentiment analysis    |
| Classes       | Positive and negative |
| Learning type | Supervised learning   |
| Input         | Tweet text            |
| Output        | Sentiment label       |

The notebook includes the dataset-loading and preprocessing workflow.

---

## ⚙️ Methodology

### 1. Logistic Regression

Implement the mathematical components of logistic regression, including:

* Sigmoid activation function
* Linear score calculation
* Cost function
* Gradient calculation
* Gradient descent optimization

The model estimates the probability that a tweet belongs to the positive sentiment class.

### 2. Feature Extraction

Convert tweet text into numerical features that can be processed by the model.

The feature-extraction stage represents text using sentiment-related information derived from the training data.

### 3. Model Training

Train the logistic regression classifier by iteratively updating its parameters using gradient descent.

### 4. Prediction

Use the trained model to classify tweets as positive or negative.

The notebook tests predictions on individual tweets and includes an opportunity to experiment with custom tweet inputs.

### 5. Model Evaluation

Evaluate the trained classifier using the provided test set and examine its classification performance.

### 6. Error Analysis

Inspect misclassified tweets to better understand where the model makes incorrect predictions and what limitations may affect sentiment classification.

---

## 🔄 Workflow

```text
Labeled Tweet Dataset
        ↓
Text Preprocessing
        ↓
Feature Extraction
        ↓
Numerical Feature Representation
        ↓
Logistic Regression
        ↓
Sigmoid Function
        ↓
Cost & Gradient Calculation
        ↓
Gradient Descent
        ↓
Trained Model
        ↓
Tweet Sentiment Prediction
        ↓
Test-Set Evaluation
        ↓
Error Analysis
```

---

## 🧠 Key Concepts

* Logistic Regression
* Binary Classification
* Sentiment Analysis
* Natural Language Processing (NLP)
* Text Preprocessing
* Feature Extraction
* Sigmoid Function
* Cost Function
* Gradient Descent
* Model Training
* Prediction
* Test-Set Evaluation
* Error Analysis

---

## 🛠️ Technologies & Tools

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Natural Language Processing utilities
* Matplotlib (for visualization, where used)

---

## 📈 Learning Outcomes

By completing this assignment, I practiced:

* Implementing a machine learning algorithm from scratch.
* Translating text into numerical representations for classification.
* Understanding how gradient descent learns model parameters.
* Applying logistic regression to a real NLP task.
* Evaluating predictions on unseen data.
* Investigating classification errors to understand model limitations.

---

## 📁 Notebook

`Logistic_Regression_Tweet_Sentiment_Analysis.ipynb`

The notebook contains the implementation, training, prediction, evaluation, and error-analysis workflow.

---

## 📚 Course Information

| Field       | Details                                 |
| ----------- | --------------------------------------- |
| Course      | Classification and Vector Spaces in NLP |
| Assignment  | Assignment 1 — Logistic Regression      |
| Task        | Tweet Sentiment Analysis                |
| Model       | Logistic Regression                     |
| Framework   | Python / NumPy                          |
| Environment | Jupyter Notebook                        |

---

## 👨‍💻 Purpose

This project is part of my NLP and machine learning portfolio, demonstrating foundational understanding of text feature extraction, logistic regression, and supervised sentiment classification.
