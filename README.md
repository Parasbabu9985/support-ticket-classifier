# Support Ticket Classification System

## Project Overview

This project automatically classifies incoming support tickets into four categories:

- Billing
- Technical
- HR
- General

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Machine Learning Approach

1. Text preprocessing
2. Subject and body combination
3. Train-test split
4. TF-IDF feature extraction
5. Logistic Regression classification
6. Model evaluation
7. New ticket prediction
8. Confidence-based human review

## Model

Logistic Regression was selected because it is fast and works effectively with high-dimensional sparse TF-IDF text features.

## Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Categories

Billing | Technical | HR | General

## Real-Time Prediction

The trained model can classify a new incoming ticket and return:

- Predicted category
- Confidence score

Low-confidence tickets can be routed to human review.

## Dataset

The dataset contains labeled support tickets with subject, body, and category fields.# support-ticket-classifier
Machine learning system for automatic support ticket classification using TF-IDF and Logistic Regression.
