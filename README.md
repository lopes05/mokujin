# Mokujin

Mokujin (v1.0.1) is a discord bot that fetches Tekken 7 framedata.  
It uses [discord.py](https://github.com/Rapptz/discord.py) v1.2.5+ and is updated to use Python 3.6+

The bot now has all the functionalities currently planned and it seems to work well and is somewhat stable. Currently, the data the bot uses is being updated to season 3 any further update will be added either on request or when we see a mistake.

Framedata acquired from RBNorway, geppopotamus and community


2019-11-19 Update: **HOX! You need to update discord.py to v1.2.5+**
## If you want to use this:

Clone this to a linux server that has Python 3.6.0+ and install the dependencies with .
```py
pip install -r requirements.txt
```
 
You need your own discord bot ([instruction](https://github.com/reactiflux/discord-irc/wiki/Creating-a-discord-bot-&-getting-a-token)) and have the tokens in the`src/resources/config.json`. You can add a feedback channel there also.


The bot only listens to and responses to messages in channels called #tekken or #raamikysely, if you want to change that, you do that in config.py, where you can also set the character aliases.
