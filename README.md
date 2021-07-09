# Natural-Language-Processing-with-Disaster-Tweets

This Kaggle competition involved using a dataset of around 10,000 tweets to train a model that would classify true disaster tweets. I first cleaned the tweets by creating functions that would remove all punctuation, URLs, emojis, and stopwards. I then decided to replace all numbers with the capital word NUMBER and lemmatize the words as well. Lastly I transformed all the words, except for the ones labeled NUMBER, to lowercase. 
After cleaning the tweets I decided to use tensorflow to tokenize and vectorize the tweets, and then I fit a neural network model on the data to obtain a model that produced an accuracy of 0.80386. 
