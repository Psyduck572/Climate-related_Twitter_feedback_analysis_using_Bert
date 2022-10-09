# Tweets_BERT-Recognition Degree Prediction
Detecting number of likes in tweets using PyTorch and pre-trained BERT model to fit a model to have a binary classification.
# Purpose
We want to develop a model to predict the recognition degree of a random tweet that is about the climate change or environmental related  infomation (based on Likes that tweets received). When  write a sentence about climate change in tweets, we will know if our argument has a degree of recognition
# Data
We use tweepy, a free API to access Twitter, to collect tweets that are related to environment/climate change. The original data is provided by CDC.  
# Model
Bert is a fancy and popular model in NLP currently. Considering the high computational consumption, we use a PyTorch build-in pre-trained model, pytorch_pretrained_bert, which was for binary classification of Twitter users' emotion analysis. We adjust some of the model's hyperparameters. 
# Evaluation Metric
We split the original raw data into training and testing set respectively with a ratio of size 7:3. Then, we calculate the accuracy by dividing the number of correct prediction by the size of the data set. Finally, we roughly got an accuracy between 0.67 to 0.83.
# Benifit  
For posters who would like to gain public awareness on their opinions on environmental change, our model can be really helpful to them. A more advanced extension of our model can be used by Twitter to rank posts based on their popularity: the most popular post, or the one with most likes, should be put at the trending section.
