# Tweets_BERT-Recognition Degree Prediction
Detecting number of likes in tweets using PyTorch and pretrained BERT model to fit a model to have a binary classification.
# Data
We use tweepy, a free API to access twitter, to collect tweets that are related to environment/climate change. The oringinal data is provided by CDC.  
# Model
Bert is a fancy and popular model in NLP currently. Considering about the high computional comsumption, we use a pytorch bulid-in pre-trained model, pytorch_pretrained_bert, which was for a binary classification of twitter user's emotion analysis. We adjust some of the model's hyperparemeters. 
# Evaluation Metric
We split the oringinal raw data into training and testing set respectively with a ratio of size in 7:3. Then, we calculate the accuracy by dividing the number of correct prediction by the size of the data set. Finally, we roughly got an accuracy that between 0.67 to 0.83.
