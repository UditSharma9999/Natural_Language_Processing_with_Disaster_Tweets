# Natural_Language_Processing_with_Disaster_Tweets

**Data Description**<br/>
What files do I need?

You'll need train.csv and test.csv.

What should I expect the data format to be?
Each sample in the train and test set has the following information:

The text of a tweet<br/>
A keyword from that tweet (although this may be blank!)<br/>
The location the tweet was sent from (may also be blank) <br/>
What am I predicting? <br/> 
You are predicting whether a given tweet is about a real disaster or not. If so, predict a 1. If not, predict a 0. <br/>

Files <br/>
train.csv - the training set <br/>
test.csv - the test set <br/>
sample_submission.csv - a sample submission file in the correct format <br/>

Columns <br/>
id - a unique identifier for each tweet<br/> 
text - the text of the tweet <br/>
location - the location the tweet was sent from (may be blank) <br/>
keyword - a particular keyword from the tweet (may be blank) <br/>
target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)<br/>
