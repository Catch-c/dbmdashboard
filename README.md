# DBM DASHBOARD
- This is built off of [NMTNathan's Discord Dashboard](https://github.com/NTMNathan/discord-dashboard). Features have been removed/modified/added to make it work with Discord Bot Maker.
- This uses Express, MongoDB and Discord.js

## REQUIREMENTS
- Node.js **v17** or later
- Discord.js **v13.6.0** or later
- Discord Bot Maker **v2** or later

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
5.  In console, run this command
```bash
npm install --save
```
6.  Add the callback URL to the Bot's OAuth2 Page. Click the save button after that.
7.  Create a **MongoDB** database. You can choose between hosting it yourself (locally, VPS) or from [MongoDB Atlas](https://www.mongodb.com/atlas/database). Paste the connection string into `MONGO_URL` in the .env file. 
            You can get the connection string by going to Database > Cluser0 > Connect > Connect using MongoDB Compass > Find connection string and put your password in <password>


