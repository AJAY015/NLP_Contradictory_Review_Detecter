# NLP_Contradictory_Review_Detecter

Project Overview
The Contradictory Review Detector is a natural language processing (NLP) project that focuses on detecting contradictory opinions within customer reviews for e-commerce products. Using machine learning algorithms such as Naive Bayes and Aspect-Based Sentiment Analysis (ABSA), the system analyzes customer reviews, identifying conflicting sentiments about specific product aspects (e.g., fit, quality, style). This provides businesses with valuable insights to refine their products and improve customer satisfaction.

Dataset
This project uses the Women's E-Commerce Clothing Reviews dataset from Kaggle, which includes:

Customer demographics.
Review texts.
Product IDs.
Ratings for various women's clothing items.
Features
Sentiment Analysis: Classifies reviews into positive, neutral, or negative sentiments using a Naive Bayes classifier.
Aspect-Based Sentiment Analysis (ABSA): Identifies specific product aspects (such as quality, fit, and style) and detects sentiments associated with those aspects.
Contradiction Detection: Detects contradictions by comparing sentiments across multiple reviews for the same product aspect.
Technologies Used
Python: Primary programming language.
Jupyter Notebook: Used for developing and running code interactively.
Natural Language Toolkit (NLTK): Used for text preprocessing tasks such as tokenization, stopword removal, and lemmatization.
Scikit-learn: Machine learning library used for implementing Naive Bayes classification.
Pandas: Data manipulation and analysis.
Matplotlib & Seaborn: Libraries used for visualization.
TextBlob: Simple library for sentiment analysis and validation.
