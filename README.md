# A-Simple-NLP-Demonstration
 
Using Yelp reviews dataset for the demonstration of NLP and prediction of reviews rating from the reviews by using the model of logistic regression and xgbclassifier. In this demo, I have done the following flow:

1. Text preprocessing: make the words to lowercase, remove punctuation, do stemming and lemmatization to standardize words
2. Text feature engineering: use sklearn CountVectorizer to vectorize the words
3. Define training & testing set and train the model
4. Get the model accuracy - LR: 0.9192 (91.9%) while XBGClassifier: 0.9176 (91.8%).
