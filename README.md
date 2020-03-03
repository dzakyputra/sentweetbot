# sentweetbot

Read the full tutorial in my [medium](https://medium.com/free-code-camp/how-to-make-your-own-sentiment-analyzer-using-python-and-googles-natural-language-api-9e91e1c493e?source=friends_link&sk=2ea3a009d7c88601d0c6f386244ea266)

Check the bot in [here](http://telegram.me/sentweetbot).

This bot will gather tweets related to the keyword that you sent, and calculate the average sentiment of those tweets (negative, neutral, or positive).

### Requirements
- python 3
- [tweepy](http://www.tweepy.org/)
- [nltk](https://www.nltk.org/)
- [Google Natural Language API](https://cloud.google.com/natural-language/)
- [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)

### Steps
Install the libraries.
```
pip3 install tweepy nltk google-cloud-language python-telegram-bot
```

Create a developer account to access Twitter API and a service account key to access Google Natural Language API, you can follow the "Getting Started" steps in [here](https://medium.freecodecamp.org/how-to-make-your-own-sentiment-analyzer-using-python-and-googles-natural-language-api-9e91e1c493e)

Configure the path.
```
export GOOGLE_APPLICATION_CREDENTIALS='[PATH_TO_CREDS.JSON]'
```

Run the program.
```
python3 main.py
```
