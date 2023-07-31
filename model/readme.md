# H1 - elon musk tweet classifier
## H2 - I have used transformers to classify the tweet dataset.
the tweet is first checked for stop words and url and signs like '@', then word by word split, after that the tweet goes through the model and is checked for scores which are 
*. positive
*. neutral
*. negative

then the scores are displayed, the higher each respective score the more it is inclined towards the respective sentiment
roBeRTa model is used, provided by hugging face under 
`cardiffnlp/twitter-roberta-base-sentiment`