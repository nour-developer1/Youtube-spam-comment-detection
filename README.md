# YouTube Spam Comment Detection

## Overview
This project aims to build a machine learning model to detect spam comments on YouTube. The dataset consists of 1,956 real messages extracted from five YouTube videos, with each comment labeled as either spam (`1`) or not spam (`0`). The goal is to clean, analyze, and classify the comments to identify spam effectively.

## Features
- **Exploratory Data Analysis (EDA):** Gain insights into the dataset through statistical analysis and visualizations.
- **Text Cleaning:** Preprocessing of comments, including removing special characters, stopwords, and performing tokenization.
- **Feature Extraction:** Text data transformed into numerical representation using `TfidfVectorizer`.
- **Model Training:** Multiple machine learning models were trained and evaluated, including:
  - Support Vector Classifier (SVC)
  - LinearSVC
  - Random Forest Classifier
- **Model Evaluation:** Performance measured using metrics like accuracy, precision, recall, and F1-score.

## Dataset
The dataset contains 1,956 YouTube comments with the following structure:
- **Comment:** The text of the YouTube comment.
- **Label:** Binary classification indicating if the comment is spam (`1`) or not spam (`0`).

## Steps in the Project
### 1. Exploratory Data Analysis
- Analyzed the distribution of spam vs. non-spam comments.
- Visualized the frequency of words and patterns in the dataset.

### 2. Data Cleaning
- Removed special characters, numbers, and punctuation.
- Lowercased all text.
- Removed stopwords to focus on meaningful words.
- Tokenized and stemmed words for standardization.

### 3. Feature Engineering
- Applied `TfidfVectorizer` to convert text data into numerical form for machine learning models.

### 4. Model Training and Evaluation
- Trained and tested the following models:
  - **SVC:** Support Vector Classifier.
  - **LinearSVC:** Linear Support Vector Classifier.
  - **Random Forest Classifier.**
- Evaluated models using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Compared the results to select the best-performing model.

## Results
- The model with the best performance was identified based on evaluation metrics.
- Insights gained from EDA and text cleaning highlighted patterns in spam comments.
