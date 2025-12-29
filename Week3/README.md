# Amazon Reviews Sentiment Analysis – Sentiment Classification

This repository contains the work completed for Week 3 – Sentiment Analysis of Amazon Reviews as part of the Data Analytics coursework.

The project focuses on classifying Amazon customer reviews into **positive** and **negative** sentiments using **Natural Language Processing (NLP)** and **Machine Learning** techniques.

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

## Dataset Overview

- **Dataset Shape:** (4914, 2)
- **Columns Used:**
  - `reviewText` – Customer review text
  - `overall` – Rating score used to derive sentiment labels
- Neutral reviews (rating = 3) were excluded for binary classification.
- Dataset was provided by the company for internship purposes.

---

## Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Matplotlib & Seaborn (for visualizations)

---

## Summary of Analysis

The project involves classifying Amazon reviews into **positive** and **negative** sentiments based on review text.

### Key Steps:
- **Data Preprocessing**
  - Removed missing and empty reviews
  - Converted ratings into sentiment labels (≥4 → positive, ≤2 → negative)
  - Removed neutral and duplicate reviews

- **Feature Extraction**
  - Applied **TF-IDF Vectorization** with:
    - `max_features = 5000`
    - English stopword removal

- **Model Training**
  - Logistic Regression model
  - 80% training data, 20% testing data

---

## Visualizations & Outputs

The following visualizations were generated to understand data distribution and model performance:

- **Sentiment Distribution Bar Chart** – shows the balance between positive and negative reviews
- **Word Clouds** – highlights frequently occurring words in positive and negative reviews
- **Confusion Matrix Heatmap** – evaluates classification performance

---

## Key Insights

- Positive reviews dominate the dataset.
- Logistic Regression achieved **94.45% accuracy** on the test set.
- The confusion matrix indicates strong performance across both sentiment classes.
- Sample predictions align well with intuitive sentiment interpretation.

---

## Future Scope

- Extend to **multi-class sentiment analysis** by including neutral reviews
- Experiment with advanced NLP models such as **BERT** or **LSTM**
- Perform sentiment trend analysis across time or product categories

---

## Metadata

- **Submitted By:** Syeda Faizah  
- **Internship:** EduLumos – Data Analytics  
- **Submission:** December 2025  

---

## Dataset Source

Dataset provided by the company for internship purposes and also publicly available on Kaggle.
