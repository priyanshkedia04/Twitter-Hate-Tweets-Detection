# Twitter-Hate-Tweets-Detection

The model was built to predict whether the Twitter Tweet is a Hate Speech or not. The project analyzed a dataset CSV file from Kaggle containing 31,935 tweets with 93% of tweets containing non-hate labeled Twitter data and 7% tweets containing hate-labeled Twitter data. The training data consisted of 9,000 non-hate tweets and 2,240 Hate tweets which were repeated 3 times to make a balanced dataset.

NLTK was used for cleaning, Stemming, and Lemmatization of the text, and removal of stop words was also done. The model was made in Python using Keras with Tensorflow in Backend. Word Embeddings were trained with 8,500 most occurring words having 32 dimensions. The model consisted of a Simple RNN layer with 8 units followed by a Dense Layer.

Training Accuracy: 98.93%

Validation Accuracy: 99.67%

Recall: 0.9165
