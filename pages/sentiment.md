# Back testing Sentiment Analysis 
If you've attempted to backtest a bot that uses sentiment analysis, you may have seen a message similiar to the following:

"Backtesting with sentiment may not work as expected."


This message is to remind you that we do not support indexing and analyzing the sentiment of articles and tweets from the past. 
When you backtest a sentiment bot, instead of using past articles it will continue to use articles from the previous day, minute, etc. that 
you have selected; thus, returning the same signal continuously for the duration of the test. 

We are working to support historical sentiment in the future, but at this team it is not worth assigning engineers to. We recommend running your 
sentiment based bots in Manta Paper for an extended period of time to validate the profitability. 
