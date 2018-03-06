# spongebot
Sponge-bot is a python based botthat replies with spongebob memes wheneer anyone posts a message in a channel. The bot is built in python and originally hosted on Heroku.

## Getting Started
* Create a [Groupme](https://dev.groupme.com/) account
* Create a [Heroku](https://heroku.com) Account
* Install [Heroku Cli](https://devcenter.heroku.com/articles/heroku-cli) on your local machine.

## Installation
1. Log into [GroupMe Dev Center](https://dev.groupme.com/bots) and create a bot and assign it to a chat. Name the bot Spongebob, (or rename it but update it in the main python file).
2. Clone or Download this project and navigate to it in your command line tool. 
3. From the command line 
```
heroku login
```
4. After you have finished logging in. You need to create the app.
```
heroku apps:create NAME-OF-BOT
```
5. This should output a URL for your bot to live at. Log back into Groupme dev center and paste this URL into your bots **Callback URL**
6. Next, copy your bots **ID** and log into your heroku account.
7.Inside Heroku, select your app, and go to settings. Scroll down and click **Reveal Config Vars** and create a variable called **GROUPME_BOT_ID** and paste in the ID of your bot from groupme and click ADD
