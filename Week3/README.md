# Amazon Reviews Sentiment Analysis – Sentiment Classification

This repository contains the work completed for Week 3 – Sentiment Analysis of Amazon Reviews as part of the Data Analytics coursework.

## Files Included

| File Name                                        | Description                                                                                         |
|--------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| amazon.csv                                       | Dataset containing Amazon customer reviews and ratings, provided by the company                     |
| SyedaFaizah_Week3_Task05_SentimentAnalysis.ipynb | Jupyter Notebook with full data preprocessing, TF-IDF vectorization, model training, and evaluation |
| SyedaFaizah_Week3_Task05_Report.pdf              | Final report with methodology, results, visualizations, and conclusions                             |

## Getting Started

To run the Jupyter Notebook:

1. **Clone the repository:**
```bash
git clone https://github.com/syeda-faizah/EDULUMOS_INTERNSHIP_TASKS.git
```
Install dependencies:

pip install pandas numpy scikit-learn


Open the notebook:

jupyter notebook SyedaFaizah_Week3_Task05_SentimentAnalysis.ipynb

## Summary of Analysis

The project focuses on classifying Amazon reviews into positive or negative sentiments based on review text and rating.

Key steps included:

Data Preprocessing: Cleaned missing and empty reviews, converted ratings into sentiment labels (≥4 = positive, ≤2 = negative), removed neutral reviews.

Feature Extraction: Transformed text data into numerical features using TF-IDF Vectorization.

Model Training: Used Logistic Regression to train on TF-IDF features.

Model Evaluation: Evaluated using accuracy and classification metrics to assess performance.

## Visualizations & Outputs

Distribution of positive and negative reviews

Sample predictions for new reviews

Accuracy and classification metrics

## Key Insights

Positive reviews dominate the dataset.

Logistic Regression achieved 94.45% accuracy on the test set.

Sample review predictions match intuitive sentiment.

## Future Scope

Include neutral sentiment classification for multi-class analysis

Experiment with advanced NLP models like BERT or LSTM

Perform sentiment trend analysis over time or across product categories

## Metadata

Submitted By: Syeda Faizah

Course: Data Analytics

Submission: December 2025

## Dataset Source

Dataset provided by the company for internship purposes, also publicly available on Kaggle
