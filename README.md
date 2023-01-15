# Discord.js
You need to install [Git](https://git-scm.com)!

Clone files into bot folder.
```
git clone --branch discordjs https://github.com/yacoreq/disbot.git
```
Move to bot diectory
```
cd disbot
```
Install node modules.
```
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
