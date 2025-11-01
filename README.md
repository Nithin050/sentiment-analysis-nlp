# Flipkart Product Review Sentiment Analysis using NLP & Machine Learning

## Overview
This project analyzes **Flipkart customer reviews** to classify sentiments (positive, neutral, or negative) based on product ratings using **Natural Language Processing (NLP)** and **Machine Learning**.  
It demonstrates a complete **end-to-end ML pipeline** — from data cleaning and text preprocessing to feature extraction (TF-IDF) and model training using **Random Forest Classifier**.

---

## Objective
To predict customer sentiment from textual product reviews and gain insights into how customers perceive Flipkart products.

---

## Technologies & Libraries Used
- **Python**
- **pandas**, **numpy** – Data cleaning and analysis  
- **matplotlib**, **seaborn** – Data visualization  
- **nltk**, **re** – Text preprocessing (tokenization, stopword removal, lemmatization)  
- **scikit-learn** – TF-IDF vectorization and RandomForestClassifier  
- **Google Colab** – Development environment  

---

## Dataset
- **Source:** Flipkart product reviews dataset (`flipkart_reviews.csv`)  
- **Features:** Review text, Product name, Rating, etc.  
- **Target:** Sentiment (derived from rating)

---

## Project Workflow
1. **Data Loading:** Load and explore the dataset using pandas.  
2. **Data Cleaning:** Handle missing values, drop duplicates, and format data types.  
3. **Exploratory Data Analysis (EDA):**
   - Distribution of product ratings  
   - Word count and frequent words visualization  
4. **Text Preprocessing:**
   - Tokenization  
   - Lemmatization  
   - Stopword removal  
5. **Feature Engineering:**
   - TF-IDF Vectorization of text data  
6. **Model Building:**
   - **RandomForestClassifier** for sentiment prediction  
7. **Model Evaluation:**
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report  

---

##  Results
 **Accuracy:** ~83% on test data  
 Good balance between precision and recall across sentiment classes  
 Clear visualizations of positive and negative term frequency  

---

## How to Run
1. **Clone this repository**
   ```bash
   git clone https://github.com/Nithin050/sentiment-analysis-nlp.git
   cd sentiment-analysis-nlp
   ```

2. **Open in Google Colab → https://colab.research.google.com**

3. **Upload the dataset flipkart_reviews.csv**

4. **Run all cells in the notebook sent_analysis_prodRev.ipynb**
