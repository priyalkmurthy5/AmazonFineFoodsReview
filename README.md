# AmazonFineFoodsReview
An NLP based analysis of VADER and RoBERTa (Transformer advantage)

# Amazon Fine Food Reviews Analysis

This project performs sentiment analysis on Amazon Fine Food reviews using natural language processing (NLP) techniques and machine learning models.

# Overview
The project involves:
- Exploratory Data Analysis (EDA) of the Amazon Fine Food reviews dataset.
- NLP processing using NLTK for tokenization and part-of-speech tagging.
- Sentiment analysis using VADER (Valence Aware Dictionary and sEntiment Reasoner).
- Utilization of the RoBERTa model for more advanced sentiment analysis.

## Getting Started

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>

2. Run the analysis notebook:
jupyter notebook SentimentAnalysis.ipynb

3. Model Training
A Logistic Regression model is trained using VADER scores and RoBERTa features to predict review scores.

# Training the model
lr.fit(X_train, y_train)
y_pred = lr.predict(X_test)
accuracy = accuracy_score(y_test, y_pred)
print(f"Model Accuracy: {accuracy}")

# Results
- VADER analysis shows a correlation between compound score and review scores.
- RoBERTa model outperforms VADER in sentiment analysis.
- Comparisons and visualizations are provided to showcase model performance.

# Conclusion
The project demonstrates the effectiveness of advanced NLP models like RoBERTa in sentiment analysis tasks. However, challenges arise in handling sarcastic or ambiguous reviews.
