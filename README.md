# Bitcoin Sentimental Analysis from Twitter
Simple first take on sentimental analysis. Python, Twitter. Lexicon-based so guaranteed to be much less accurate.


## Issues with Accuracy (assumptions)
- Lexicon-based, so it has trouble unpacking crypto finance talk ("bitcoin finished deep in the red today")
- Twitter is heavily sarcasm-based, which lexicon-based approaches struggle with
- TextBlob cannot interpret emojis
- No (scalable) way of backtesting accuracy of labels
