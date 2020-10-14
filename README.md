# Send a thread of tweets with Tweepy
[![GitHub](https://img.shields.io/github/license/jacobmannix/tweepythread?color=blue)](LICENSE)
[![GitHub top language](https://img.shields.io/github/languages/top/jacobmannix/tweepythread)](https://github.com/JacobMannix/kubernetes-stafford)
[![GitHub last commit](https://img.shields.io/github/last-commit/jacobmannix/tweepythread)](https://github.com/JacobMannix/kubernetes-stafford/commits/master)

> <b> Python function that uses the Tweepy package in order to send a thread of tweets. </b>

![ThreadVNormalTweets](images/threadvnormaltweets.jpeg)

#

### Prerequisites
- A [Twitter Developer Account](https://developer.twitter.com/) in order to get Twitter API keys.
- [tweepy](https://www.tweepy.org/) python package installed.
```python
pip install tweepy
```
#
### Variables in '.env'
See the docs: [python-dotenv](https://github.com/theskumar/python-dotenv)
```python
API_KEY = "YOUR_KEY_HERE"
API_SECRET = "YOUR_KEY_HERE"
API_ACCESS_TOKEN = "YOUR_KEY_HERE"
API_ACCESS_SECRET = "YOUR_KEY_HERE"
TWITTER_ACCOUNT = "YOUR_@TWITTER_HERE"
```

#
### Call Function
Place tweepythread.py in working directory
```python
from tweepythread import tweepyThread

tweepyThread(user, list, ckey, csecret, atoken, asecret)
```