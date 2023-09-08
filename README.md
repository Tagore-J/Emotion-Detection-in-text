# Emotion-Detection-in-text
Data consists of text from various sources, with a respective emotion associated with it. The target is to build a model that can evaluate the overall emotion in the text on a given set of classes. 

Data: 
The data is primarily collected from official government websites of countries such as USA, UK, Russia and China. The text is usually the speech of the country's delegate in a event. Each text has a emotion of classes- Joy, Optimistic, Neutral, Upset associated to it. The dataset consists of Country, Date, Speaker, Headline,	Text_of_Speech,	Designation, Running President/PM, Speech Link, Emotion	Context.

This repo consists of various models consisting of word vectorizing techniques such as TF-IDF, Count Vectorizer, Word2Vec, Doc2Vec followed by machine learning and deep learning algorithms with hyperparameter tuning. 
1. TF-IDF Vectorizer:
   1.1. RandomForestClassifier 
   1.2. XGBClassifier
   1.3. MultinomialNB
   1.4. Logistic Regression
   1.5. DecisionTree Classifier
   1.6. Support Vector Classification
   1.7. LinearSVC
   1.8. KNeighbors Classifier
2. CountVectorizer:
   2.1. MultinomialNB
   2.2. XGBClassifier
3. Word2Vec:
   3.1. Support Vector Classification
   3.2. RandomForestClassifier
4. Doc2Vec:
   4.1. LogisticRegression
   
