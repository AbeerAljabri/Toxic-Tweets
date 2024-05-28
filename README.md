# Toxic-Tweets
# Identifying Toxicity in Tweets Using Machine Learning and Persona Analysis

## Overview
This project leverages the Toxic Tweets Dataset from Kaggle to identify and mitigate online toxicity using advanced natural language processing (NLP) techniques and machine learning models. By expanding our dataset with contextual persona information, we aim to enhance the accuracy of toxicity detection.

### Objectives
- Identify Toxic Content: Develop models to classify toxic content in tweets.
- Evaluate Model Performance: Use metrics such as F1 score, precision, recall, and accuracy to evaluate model effectiveness.
- Incorporate Persona Analysis: Introduce a new feature, 'persona', to provide contextual information and assess its impact on toxicity identification.

### Methodology
- Baseline Models: Implement Logistic Regression (LR) and Support Vector Classifier (SVC) as baseline models for initial toxicity detection.
- Advanced Models: Utilize BERT (Bidirectional Encoder Representations from Transformers) models for a more sophisticated approach, comparing their performance against baseline models.
- Dataset Expansion: Add a 'persona' column to the dataset using the Riveter package, which analyzes social dynamics between personas mentioned in the texts. This feature provides additional contextual data that may influence toxicity detection.
- Evaluation Metrics: Evaluate the models based on F1 score, precision, recall, and accuracy to ensure a comprehensive assessment of their performance.
