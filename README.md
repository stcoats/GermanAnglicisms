# GermanAnglicisms

The file "Anglicism_Matchlist_July18.txt" is a list of potential German-language infinitives and past participles generated from English-language verbs.

The files "GermanTweets_aa" to "GermanTweets_af" should be joined to create a compressed list of the Tweet IDs of 36,240,530 German-language tweets collected from Twitter's APIs in April 2018. 

To join the files, download them to an empty directory and (in Linux) run `cat German* > GermanTweets.tar.gz`.
Decompress the resulting file to get the large list of Tweet IDs. 

To download the tweets from Twitter, feed in the Tweet IDs using [Tweepy](https://github.com/tweepy/tweepy), [Twarc](https://github.com/docnow/twarc), or a similar tool.

If you use the resources, please cite [this paper].
