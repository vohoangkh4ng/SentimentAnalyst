# Sentiment Analysis Report

## Introduction
This project applies Sentiment Analysis to assess customer perceptions of banking services. The dataset was collected from customer reviews of banks in India, with the goal of understanding customer satisfaction and sentiment trends.

## Objectives
- Apply machine learning techniques to analyze and classify sentiments from customer reviews.
- Compare classification models such as **Logistic Regression**, **Random Forest**, and **CatBoost** to identify the optimal model for this task.

## Research Methods
- **Data Preprocessing**: Steps include sentiment labeling, removing common words, normalizing data, and reducing dimensionality using PCA.
- **Sentiment Analysis**: Tools like VADER and WordCloud were used to analyze keywords and determine the positive, negative, and neutral sentiments of the reviews.
- **Classification Models**: Trained and evaluated various sentiment classification models on the processed dataset. Models were optimized using **Grid Search** for better accuracy.
- **Model Evaluation**: Models were compared on metrics such as accuracy, precision, recall, and F1-score.

## Results
- **Logistic Regression** and **Random Forest** models achieved high accuracy, with scores of 92% and 91%, respectively.
- **CatBoost** showed lower accuracy and had difficulties with correctly classifying sentiment categories.
- Detailed results on precision, recall, and F1-score for each model are included in the full report.

## Future Development
- Collect additional data and expand the classification categories to capture a wider range of sentiments.
- Explore the model's applicability to languages beyond English, and extend its use for analyzing sentiments based on other customer characteristics.

## Tools and Libraries
- Language: Python
- Libraries: `scikit-learn`, `NLTK`, `WordCloud`, `Gradio`

## Demo
An interactive demo interface built with **Gradio** allows users to input text and receive instant sentiment predictions based on the Logistic Regression model.

## Repository Contents
- `data/`: Folder containing the dataset used in the project.
- `notebooks/`: Jupyter notebooks with data preprocessing, analysis, and model training code.
- `models/`: Saved model files for Logistic Regression, Random Forest, and CatBoost.
- `app.py`: Gradio app script for the interactive sentiment analysis demo.
- `README.md`: Project overview and instructions (this file).

---
