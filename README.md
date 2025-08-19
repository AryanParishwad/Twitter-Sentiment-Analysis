# Twitter Sentiment Analysis using KNN and its Variants

This repository contains the code and documentation for my formal research internship project at MES Wadia College of Engineering. The goal of this project was to analyze and classify the sentiment of tweets as positive, negative, or neutral using various K-Nearest Neighbors (KNN) algorithms.

## 📖 Project Overview
This project involves an end-to-end NLP pipeline:
1.  **Data Preprocessing:** Cleaning and normalizing raw text data from the `Tweets.csv` dataset.
2.  **Feature Extraction:** Converting the cleaned text into numerical vectors using TF-IDF.
3.  **Model Implementation:** Building and evaluating several KNN models to find the most effective classifier.

## 🛠️ Tech Stack
- Python
- Scikit-learn
- Pandas & NumPy
- NLTK (Natural Language Toolkit)
- Jupyter Notebook

## 🔬 Methodology
The preprocessing pipeline included several key steps to prepare the text data for modeling:
- **Normalization:** Converted all text to lowercase.
- **Cleaning:** Removed URLs, punctuation, and English stop-words to eliminate noise.
- **Stemming:** Applied Porter Stemming to reduce words to their root form, standardizing the vocabulary.

The project then implemented and compared the accuracy of multiple KNN variants, including Simple KNN, Weighted KNN, and LM-KNN.

## 📂 Files in this Repository
- `knn5.ipynb`: The Jupyter Notebook containing the full Python code for the analysis.
- `Tweets.csv`: The dataset used for training and testing the models.
- `Aryan_final_report.pdf`: The official, detailed report submitted for the internship.
