# Restaurant-Clustering-and-Sentiment-Analysis-Unsupervised-ML-Model
Table of Contents

Introduction

Project Overview
Preprocessing Data
Feature Engineering
ML Model Implementation
Conclusion

Introduction

Welcome to the Machine Learning Capstone Project, a complete exploration of the machine learning lifecycle—from data preparation to model implementation and evaluation. This project demonstrates best practices in data preprocessing, feature engineering, and applying ML models to derive actionable insights.

Project Overview

Data Collection: Collected datasets including customer reviews, restaurant details, and other relevant attributes.
Data Preprocessing: Handled missing values, cleaned data, and prepared it for analysis.
Feature Engineering: Created new features, removed redundant ones, and applied text preprocessing techniques to enhance data quality.
ML Model Implementation: Implemented K-Means Clustering and Latent Dirichlet Allocation (LDA) for insights and topic modeling.
Model Evaluation: Evaluated models using metrics such as Silhouette Score, ROC-AUC, precision, and recall.
Preprocessing Data
Collected reviews, restaurant information, and other relevant data.
Performed extensive data cleaning and missing value handling.

Applied text preprocessing:

Expanded contractions
Lowercased text
Removed punctuation, URLs, digits, stopwords, and extra whitespace

Feature Engineering

Created new features to reduce multicollinearity.
Performed sentiment analysis on reviews (positive/negative classification based on average ratings).
Log-transformed the 'Cost' feature to correct positive skewness.

ML Model Implementation

1. K-Means Clustering:

Clustered data into 6 groups to understand patterns in restaurant features.

2. Latent Dirichlet Allocation (LDA):

Applied topic modeling to extract meaningful insights from customer reviews.

Conclusion

Improved clustering results by carefully selecting the number of clusters (K).
Fine-tuned the LDA model for better topic modeling and higher Silhouette Scores.
Conducted extensive model evaluation using metrics like ROC-AUC, precision, and recall.

