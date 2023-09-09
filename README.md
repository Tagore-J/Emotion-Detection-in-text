# Emotion-Detection-in-text
Data consists of text from various sources, with a respective emotion associated with it. The target is to build a model that can evaluate the overall emotion in the text on a given set of classes. 

Data: 
The data is primarily collected from official government websites of countries such as USA, UK, Russia and China. The text is usually the speech of the country's delegate in a event. Each text has a emotion of classes- Joy, Optimistic, Neutral, Upset associated to it. The dataset consists of Country, Date, Speaker, Headline,	Text_of_Speech,	Designation, Running President/PM, Speech Link, Emotion	Context.

This repo consists of various models consisting of word vectorizing techniques such as TF-IDF, Count Vectorizer, Word2Vec, Doc2Vec followed by machine learning and deep learning algorithms with hyperparameter tuning. 
MACHINE LEARNING-
1. TF-IDF Vectorizer: RandomForestClassifier, XGBClassifier, MultinomialNB, Logistic Regression, DecisionTree Classifier, Support Vector Classification, LinearSVC, KNeighbors Classifier
2. CountVectorizer: MultinomialNB, XGBClassifier
3. Word2Vec: Support Vector Classification, RandomForestClassifier
4. Doc2Vec: LogisticRegression

DEEP LEARNING-
1. TF-IDF Vectorizer: LSTM, GRU
2. Glove Vectorizer: LSTM
