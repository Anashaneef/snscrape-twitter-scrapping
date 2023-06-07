# Twitter Scrapping Use Snscrape

## About This Repo
This repository explains how to use **sntwitter**, which is part of **snscrape**, for scrapping twitter data. In the example I tried scrapping twitter with the keyword "russian inflation". I only took 10 twitter data related to the keyword. The data I took was only tweets and also the time of the tweet. However, you can modify the program code if you want to retrieve other parts of the tweet.

## Documentation
If you want to run the code locally, you must install some library:
1. Pandas

```
pip install pandas
```

2. Snscrape

```
pip3 install git+https://github.com/JustAnotherArchivist/snscrape.git
```

3. Cleantext

```
pip install clean-text[gpl]
```