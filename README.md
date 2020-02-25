# emojiprediction

## Included Files

### DataScraping and Cleaning
**data_grab.py** - Used for scraping real-time tweets and could be setted to different emoji for searching if tweets including the specific emoji.\
**adding_label.py** - After saving the real-time tweets to local machine, we transforming each emoji into specific number and remove emoji in each tweet, adn remove all non-English tweets in our dataset.\
**data_clean.py** - Used this step to clean and remove all unexpected characters, stopping words, and punctuations. Meanwhile, we exclude the tweets with words count less than 5.

### Modeling

** Each file (python or jupyter) is one modeling


## Reference Library
#### tweepy - https://tweepy.readthedocs.io/en/latest/
#### Keras - https://keras.io/
#### fastText - https://fasttext.cc/
#### textblob - https://textblob.readthedocs.io/en/dev/
#### preprocessor - https://pypi.org/project/tweet-preprocessor/
#### nltk - https://www.nltk.org/
#### seaborn - https://seaborn.pydata.org/
#### xgboost - https://xgboost.readthedocs.io/en/latest/


