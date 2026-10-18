# Twitter-sentiment-analysis

It started with me getting a dataset from kaggle on Twitter Sentiment Analysis, so I built a basic model that could actually analysis the sentiment of roughly 160,000 tweets.
I loaded and cleaned the data into a pandas dataframe and dropped any rows with missing data, I then split the data into train_test datasets(80% to 20&)
Vectorizing it with TfidfVectorizer to convert the words to numerical values, then proceeded to train it using the Logistical-Regression model from sklearn to find mathematical patterns connecting word scores to positive, neutral, negative sentiment
For the next step I evaluated the models predictions of the unseen test set (y_pred)and the true answers(y_test) to calculate overall, accuracy, precision and recall.
Finally saved and exported it with joblib for reusing.
