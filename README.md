# MwebembeziNicole_M23B23.026_BIGDATA-EXAM
Scalable Big Data sentiment and trend analysis of social media using the Sentiment140 dataset. The project applies distributed preprocessing, TF-IDF feature engineering, and linear classification models to extract sentiment insights for business decision-making while addressing ethical and privacy considerations.

# Scalable Social Media Sentiment Analysis (Big Data)

## Overview
This project presents a scalable Big Data analytics solution for large-scale social media sentiment and trend analysis using the **Sentiment140 dataset**, which contains approximately **1.6 million Twitter posts**. The analysis follows the **CRISP-DM methodology** and demonstrates how Big Data platforms and scalable machine learning models can be applied to extract meaningful sentiment insights from high-volume, unstructured text data.

The project was developed using **Google Colab** and version-controlled using **GitHub** to ensure reproducibility and transparency.

---

## Objectives
- To preprocess and transform large-scale social media text data using scalable techniques.
- To apply and compare scalable sentiment classification models on high-volume data.
- To evaluate model performance, optimisation impact, and suitability for Big Data analytics.

---

## Dataset
- **Name:** Sentiment140
- **Source:** Stanford University (via Kaggle)
- **Size:** ~1.6 million tweets
- **Labels:** Positive (4) and Negative (0)
- **Link:** https://www.kaggle.com/datasets/kazanova/sentiment140

The dataset includes unstructured tweet text and metadata such as timestamps and user identifiers, making it suitable for sentiment analysis and trend detection.

---

## Big Data Characteristics
The dataset demonstrates all six Big Data characteristics:
- **Volume:** Millions of tweets
- **Velocity:** Time-stamped data enables stream simulation
- **Variety:** Text and metadata
- **Veracity:** Labeled sentiment improves reliability
- **Value:** Enables sentiment trend analysis
- **Variability:** Language and sentiment change over time

---

## Data Processing
- Removal of URLs, mentions, and special characters
- Text normalisation and cleaning
- Feature analysis using tweet length
- Stratified 80/20 train–test split to preserve class balance

---

## Modelling and Analytics
### Feature Engineering
- **TF-IDF** with a maximum of 50,000 features

### Models Implemented
- Logistic Regression (baseline and optimised)
- Linear Support Vector Machine (SVM)

### Optimisation
- Regularisation tuning
- Reduced iteration limits
- Parallel execution

Optimised Logistic Regression achieved the best balance between predictive performance and computational efficiency.

---

## Key Results
- Accuracy ≈ **0.818**
- F1-score ≈ **0.818**
- Very low prediction latency, suitable for near real-time sentiment inference
- Balanced class performance and stable generalisation

---

## Business Application
The analytical results support **real-time brand and event sentiment monitoring**, enabling organisations to:
- Track public opinion during product launches or campaigns
- Detect sudden sentiment shifts
- Support data-driven marketing, public relations, and customer engagement decisions

---

## Ethical and Privacy Considerations
- Analysis is performed at an aggregated level to avoid individual profiling
- Personal identifiers are ignored or anonymised
- Model limitations and potential biases are acknowledged
- Data usage aligns with ethical research standards and data protection principles

---

## Tools and Technologies
- Python
- Google Colab
- Pandas
- Scikit-learn
- Matplotlib
- GitHub

---

## Repository Structure

