# Russian Troll Tweets

## Context
As part of the House Intelligence Committee investigation into how Russia may have influenced the 2016 US Election, Twitter released the screen names of almost 3000 Twitter accounts believed to be connected to Russia’s Internet Research Agency, a company known for operating social media troll accounts. Twitter immediately suspended these accounts, deleting their data from Twitter.com and the Twitter API. A team at NBC News including Ben Popken and EJ Fox was able to reconstruct a dataset consisting of a subset of the deleted data for their investigation and were able to show how these troll accounts went on attack during key election moments. This dataset is the body of this open-sourced reconstruction.

## Content
The dataset contains two CSV files. tweets.csv includes details on individual tweets, while users.csv includes details on individual accounts.

To recreate a link to an individual tweet found in the dataset, replace user_key in https://twitter.com/user_key/status/tweet_id with the screen-name from the user_key field and tweet_id with the number in the tweet_id field.

Following the links will lead to a suspended page on Twitter. But some copies of the tweets as they originally appeared, including images, can be found by entering the links on web caches like archive.org and archive.is.
