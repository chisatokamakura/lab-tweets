# www.trumptwitterarchive.com


## Word Frequency Analysis

| phrase            | percent of tweets |
| ----------------- | ----------------- |
|           america | 08.85             |
|                me | 41.88             |
|             obama | 05.51             |
|               the | 56.86             |
|             trump | 32.45             |

The table above shows the percentage of tweets containing these selected keywords across the full dataset of Trump's tweets, using the latest version of his data.

![Word Percentages](word_percentages.png)


## Extra Credit: Tweets by Time of Day

This plot shows the number of Trump's tweets sent during each hour of the day (0–23).

![Tweets by Hour](time_of_day.png)





This repo will automatically update once every hour.

Only the condensed_2017.json.zip and master_2017.json.zip will change. 

Favorite counts and retweet counts will be updated for the latest 100 tweets.

Example data from the condensed JSON files:

  {
    "source": "Twitter for iPhone",
    "id_str": "838899465390018560",
    "text": "I am a monster-man!",
    "created_at": "Mon Mar 06 23:49:53 +0000 2017",
    "retweet_count": 8021,
    "in_reply_to_user_id_str": null,
    "favorite_count": 33632,
    "is_retweet": false
  }
  
The master JSON files contain the full response from Twitter's API. Some of the files are quite large and unwieldy.



