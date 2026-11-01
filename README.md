# Sentiment Analysis using NLP

## Project Overview
This project uses Natural Language Processing (NLP) and machine learning to classify movie reviews as positive or negative.

The objective is to understand text sentiment and automatically identify opinions expressed in movie reviews.

## Dataset
- **Dataset:** IMDb Movie Reviews
- **Total reviews:** 50,000
- **Training reviews:** 25,000
- **Testing reviews:** 25,000
- **Classes:** Positive (1) and Negative (0)
- **Source:** [IMDb Dataset – Stanford](https://ai.stanford.edu/~amaas/data/sentiment/)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Workflow
1. Dataset loading
2. Exploratory Data Analysis
3. Text cleaning and preprocessing
4. TF-IDF feature extraction
5. Model training
6. Model evaluation
7. Custom review prediction
8. Model saving and loading

## Text Preprocessing
- Convert text to lowercase
- Remove HTML tags
- Remove URLs
- Remove special characters
- Remove extra spaces

## Feature Extraction
TF-IDF (Term Frequency–Inverse Document Frequency) converts text reviews into numerical features for machine learning.

Configuration:
- Maximum features: 10,000
- N-gram range: (1, 2)
- Minimum document frequency: 2
- Maximum document frequency: 0.95

## Machine Learning Models
- Logistic Regression
- Multinomial Naive Bayes

## Model Evaluation
Models were compared using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

The best model was selected based on the F1 score.

## Project Files
- `Sentiment_Analysis.ipynb` — Complete notebook.
- `sentiment_analysis_model.pkl` — Saved TF-IDF vectorizer and trained model.
- `requirements.txt` — Required Python libraries.

## How to Run
1. Open the notebook in Google Colab.
2. Run the cells in sequence.
3. The IMDb dataset is loaded directly from its online source.
4. Review model evaluation and custom sentiment predictions.

## Future Improvements
- Try deep learning models such as LSTM and BiLSTM.
- Experiment with transformer models such as BERT.
- Build a web application for real-time sentiment prediction.

## Author
Akhil A V
Integrated MSc Computer Science (AI & ML)
