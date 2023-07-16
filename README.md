# TwitterSentiment

Twitter comment sentiment classification into Hate/Non-Hate. I have used GloVe for word vectors and a simple LSTM architecure. The data used for this task was taken from Twitter Sentiment Analysis (https://www.kaggle.com/datasets/arkhoshghalb/twitter-sentiment-analysis-hatred-speech) and has been uplaoded on this repo. 

# Instructions to run

Create a virtual envirnoment and install all the packages in requirements.txt. Run all the cells in the notebook to load, preprocess, train and save the model. The best model will be saved and loaded from the "models/" directory. Run the "predictor()" cell you test the classifer on your own text.
