# Fake_News_Prediction

The goal of this project is to predict whether a news is fake or not. For this purpose, the following steps were taken:
* Loading first the data (reindexing, dealing with missing values, etc.)
* Preprocessing the title text by removing stop words, lowering the letters etc.
* Applying a bag of words technique (`CountVectorizer`) to convert text data into numerical data (big matrix). Although `tfidfVectorizer` can be used. 
* Applying some machine learning classification algorithms (`MultinomialNB`, `PassiveAggressiveClassifier`)

This project was carried out as part of Udemy course: Data Science Real-World Use Cases - Hands On Python.
