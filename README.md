# Spam-Email-Classifier

This repository features a machine learning project focused on classifying emails as **spam** or **not spam** using a Naive Bayes classifier. It's designed as an introductory NLP project to showcase text preprocessing and binary classification.

## Overview

The goal is to build a model that accurately predicts whether an email is spam based on its text content. The project walks through every step from data loading to model evaluation using a clean, reproducible approach.

## Project Link

The full workflow, from preprocessing to model evaluation, is documented in the Jupyter Notebook:

**Notebook**: [`spamclassifier.ipynb`](./spamclassifier.ipynb)

## Project Features

- **Data Loading**: Reading the spam dataset (CSV format with labeled text messages).
- **Data Cleaning**: Lowercasing, punctuation removal, stopword removal, and tokenization.
- **Feature Extraction**: Text vectorization using CountVectorizer.
- **Model Training**: Training a Multinomial Naive Bayes classifier.
- **Model Evaluation**:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)
- **Visualization**: Confusion matrix heatmap for performance interpretation.

## Dataset

The dataset contains SMS messages labeled as:
- **Spam** – Unwanted or promotional content.
- **Ham** – Legitimate messages.

Each message undergoes preprocessing to improve model performance.

## Key Findings

- Naive Bayes achieved strong performance with high accuracy.
- Excellent precision and recall, particularly for identifying spam.
- Minimal misclassification, making it suitable for real-world filtering.

## How to Use

To run the project locally:

1. Clone or download this repository.
2. (Optional) Set up a virtual environment.
3. Install required dependencies.
4. Launch the notebook:
