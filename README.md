# DBM DASHBOARD
- This is built off of [NMTNathan's Discord Dashboard](https://github.com/NTMNathan/discord-dashboard). Features have been removed/modified/added to make it work with Discord Bot Maker.
- This uses Express, MongoDB and Discord.js

## REQUIREMENTS
- Node.js **v17** or later
- Discord.js **v13.6.0** or later
- Discord Bot Maker **v2** or later
- MongoDB Database (Host yourself, or grab a free one with [Mongo Atlas](https://www.mongodb.com/atlas/database))

## SETUP
1.  Create a folder on your computer, then type the following console command to clone the original dashboard.
```bash
git clone https://github.com/NTMNathan/discord-dashboard
```
```bash
Alternatively, visit https://github.com/NTMNathan/discord-dashboard. Click 'Code' and 'Download Zip'
```
2.  Create a folder on your computer, then type the following console command to clone this repository 
```bash
git clone https://github.com/Catch-c/dbmdashboard
```
```bash
Alternatively, on this page click 'Code' and 'Download Zip'
```
3.  Move the contents of this repositorys folder 'dashboard' into your https://github.com/NTMNathan/discord-dashboard folder. Make sure to replace the duplicate files.
4.  Rename `example.env` to `.env` and fill out `TOKEN` `CLIENT_ID` & `CLIENT_SECRET` with the values from your applications **OAuth2** and **Bot** page. https://discord.com/developers/applications/ | SAVE THIS FILE.
5.  Edit `SUPPORT_SERVER` `BOT_DESCRIPTION` `FEATURE_TITLE` `FEATURE_DESCRIPTION` to your liking in the `.env` file (Make sure to change feature title and description for all 6 features)
6.  In console, run this command
```bash
npm install --save
```
6.  Add the callback URL to the Bot's OAuth2 Page. Click the save button after that.
7.  Create a **MongoDB** database. You can choose between hosting it yourself (locally, VPS) or from [MongoDB Atlas](https://www.mongodb.com/atlas/database). Paste the connection string into `MONGO_URL` in the `.env` file. 
            You can get the connection string by going to Database > Cluser0 > Connect > Connect using MongoDB Compass > Find connection string and put your password in <password> | SAVE THE .env FILE
8.  In console, run the following command
```bash
npm run deploy
```
9.  In console, run the following command
```bash
node bot
```
10. Add the commands and events from this repository into your Discord Bot Maker. Save, and run the bot.
11. Access the dashboard at localhost:3000 or at your site.
            
            
## SUPPORT & SUGGESTIONS
I suggest you watch the [video tutorial] as that will most likely answer your question as it goes through every step.
If you still need help, shoot me a dm on Discord `catch##2601`

If you have a suggestion, shoot me a dm on Discord `catch#2601`

