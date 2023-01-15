# Discord.js
You need to install [Git](https://git-scm.com)!
```
//clone files into bot folder
git clone --branch discordjs git@github.com:yacoreq/disbot.git

//install node modules
npm i
```
Edit `config.json`
```
{
 "clientId": "bot-id-here",
 "guildId": "guild-id-here",
 "token": "bot-token-here"
}
```
Create a file `start.bat` (for Windows) or `start.sh` (for Linux) in the bot folder and paste the code below in that file.
```
node index.js
```
