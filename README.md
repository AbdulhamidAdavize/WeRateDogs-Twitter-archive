# WeRateDogs-Twitter-archive
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog[1]. Each day features a different dog picture and a rating above 10. They downloaded their twitter archive and provided it to Udacity so that each student can perform a data wrangling project with it.
### About Dataset
There are three datasets gathered for this project. 
1. Image prediction dataset: This file is contains predictions of image present in each tweet according to a neural network. It is hosted on Udacity's servers and was downloaded programmatically using the Requests library.
2. The WeRateDogs Twitter archive: this is a file on hand downloaded manually
3. Tweet_json.txt: this file was gathered Using the tweet IDs in the WeRateDogs Twitter archive, and then querying the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file as shown below.
### conclusions
1. There is a high correlation between favorite count and retweet count.
2. There is a very low correlation between ratings and favorite count which means they have no relatonship.
3. Dogs in the puppo dog stage have most likes and ratings which means pictures in puppo stage tend to get more likes and ratings and equally more retweets on average since their is a high correlation between favorite_count and retweet_count.
