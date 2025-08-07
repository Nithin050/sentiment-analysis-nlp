Flipkart Product Review Sentiment Analysis

This project analyzes customer reviews from Flipkart to determine sentiment based on product ratings using Natural Language Processing (NLP) and Machine Learning. The primary model used is RandomForestClassifier.

Overview:-
Goal: Predict sentiment (based on ratings) from customer reviews.
Dataset:- flipkart_reviews.csv
Technique:- Text Cleaning, TF-IDF, and Random Forest Classification


Steps Performed:-

1. Data Loading: Uploading CSV and reading using pandas.
2. Data Cleaning:
   - Dropping nulls
   - Type checking and EDA
3. Exploratory Data Analysis (EDA):
   - Rating distribution
   - Word count visualization
4. Text Preprocessing:
   - Tokenization
   - Lemmatization
   - Stopword removal
5. Feature Engineering:
   - TF-IDF vectorization
6. Model Building:
   - Using RandomForestClassifier
7. Evaluation:
   - Accuracy Score
   - Classification Report
   - Confusion Matrix


Accuracy Achieved:-
Accuracy: ~83% on test data

Steps to Run:-
1. Upload your dataset named flipkart_reviews.csv.
2. Run each code block step-by-step on https://colab.research.google.com.
3. Final model output will show accuracy, confusion matrix, and classification report.

Files in the Repo:-
- sentiment_analysis.ipynb – Colab notebook with full pipeline
- flipkart_reviews.csv – Dataset
- README.md – Project overview


GitHub & Colab Links:-
- GitHub Repo: https://github.com/Nithin050/sentiment-analysis-nlp


Author:-
Nithin Nair 
Aspiring AI/ML Developer | Final Year BSc CS  
https://github.com/Nithin050/sentiment-analysis-nlp
nithin.2005nair@gmail.com
