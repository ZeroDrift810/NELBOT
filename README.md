# snallabot

## Setup

### Adding the bot to your server

Add the snallabot to your server by clicking [here](https://discord.com/api/oauth2/authorize?client_id=970091866450198548&permissions=268445712&scope=applications.commands%20bot). This will add the following slash commands: 

```
/import_league
/create_game_channels
/clear_game_channels
```

### Add your madden league

This process requires to download files from https://maddenexporter.herokuapp.com/ . 

If you do not have an account on madden exporter got ahead and create one. Then, navigate to Madden Data or https://maddenexporter.herokuapp.com/USERNAME (replace USERNAME with the username your created)

If you do not have the madden companion app you will need to download that from the app store and sign into your EA account. 

Then do the following steps
1. Find your league in the Madden companion app and click on it
2. Navigate to Export data section
3. Type in the madden exporter url. It will be on the Madden Data page of the exporter and be the following URL: https://mxport.herokuapp.com/USERNAME (again replace that with your username). *unfortunately you have to type this because EA is ass and wont let you copy and paste)
4. choose league info, weekly stats, and scroll down on the week number to find All Weeks and choose that.
5. Finally export!
6. (if something fails first try retrying it can just error sometimes)
7. you will see your data on the madden data page on a refresh, make sure you wait until its all down and hit the download JSON
8. With this zip file, unzip it however you choose
9. finally, run the /import_league command in your discord, the two required options are the following files: schedules.json and teams.json. Both of those are in the zip file
10. run the command, if you see uploaded :) then you are all set! if it fails, well contact me I will see what goes wrong :) 

## Commands

`/import_league schedules teams` - imports the league into the bot. This only has to be done once per season! If you do it multiple times nothing bad happens tho! so if you want to update every playoff week that is okay

`/create_game_channels week category` - This creates game channels for that specific week. It will only create game channels for the regular season and it will create them under the desired category

`/clear_game_channels category` - this clears game channels under a category. it will not clear any channels that do not contain the word 'vs' so FW channels and such are OK
