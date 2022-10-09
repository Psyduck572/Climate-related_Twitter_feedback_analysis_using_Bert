# Tweets_BERT-Recognition Degree Prediction
Detecting number of likes in tweets using PyTorch and pre-trained BERT model to fit a model to have a binary classification.
# Data
We use tweepy, a free API to access Twitter, to collect tweets that are related to environment/climate change. The original data is provided by CDC.  
# Model
Bert is a fancy and popular model in NLP currently. Considering the high computational consumption, we use a PyTorch build-in pre-trained model, pytorch_pretrained_bert, which was for binary classification of Twitter users' emotion analysis. We adjust some of the model's hyperparameters. 
# Evaluation Metric
We split the original raw data into training and testing set respectively with a ratio of size 7:3. Then, we calculate the accuracy by dividing the number of correct prediction by the size of the data set. Finally, we roughly got an accuracy between 0.67 to 0.83.
