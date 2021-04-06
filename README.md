# mushy-twitch-bot
Mushy dumpling twitch bot that can do fun stuff.

## Creating a mushy twitch bot
- Create a twitch account for the bot.
- Log in to that account
- Create an oath token by clicking this [link](https://twitchapps.com/tmi/)
- Authorize and copy the oath password and store it on a .env file under a variable name TWITCH_OATH_TOKEN like so.
```
TWITCH_OATH_TOKEN=oath:sda.....
```
- While you are in that .env file, also add the following details.
```
TWITCH_USERNAME=<fill in your twitch bot account username>
TWITCH_CHANNEL=<fill in the twitch channel you want your bot to be in>
```
- Add the .env file to the root (mushy-twitch-bot) folder.
- then run the command: 
```
node index.js
```