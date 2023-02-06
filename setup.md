# Setup

## Adding the bot to your server

Add the snallabot to your server by clicking [here](https://discord.com/api/oauth2/authorize?client_id=970091866450198548&permissions=268438608&scope=bot%20applications.commands).

## Setup your league

This step has to be done every SEASON of your league. Once you reach preseason week 1 you can do this setup again (any number of times after that it wont matter).

### Recommended Way with Madden Companion App

Now the bot has been added to your discord server do the following:

1. run `/league_export`, this will give you a URL that will be the export URL. whenever you run this command it will give you the same URL!
2. Open the Madden Companion App
3. Find your league in the app and click on it
4. Navigate to the Export section
5. In the web url box, type in the export URL you were given. I am sorry its so long!! but type carefully :)!!!
6. Check the league info, and weekly stats boxes
7. For export week, export All Weeks (scroll to the bottom of the weeks!)
8. Finally, export! Once it is done, the bot is all setup to use

### Non Recommended way with manual file import

The above method is much easier, but if things go wrong this is the other option to add the league to the bot.

This process requires to download files from https://maddenexporter.herokuapp.com/ .

If you do not have an account on madden exporter got ahead and create one. Then, navigate to Madden Data or https://maddenexporter.herokuapp.com/USERNAME (replace USERNAME with the username your created)

If you do not have the madden companion app you will need to download that from the app store and sign into your EA account.

Then do the following steps

1. Find your league in the Madden companion app and click on it
2. Navigate to Export section
3. Type in the madden exporter url. It will be on the Madden Data page of the exporter and be the following URL: https://mxport.herokuapp.com/USERNAME (again replace that with your username). _unfortunately you have to type this because EA is ass and wont let you copy and paste_
4. choose league info, weekly stats, and scroll down on the week number to find All Weeks and choose that.
5. Finally export!
6. (if something fails first try retrying it can just error sometimes)
7. you will see your data on the madden data page on a refresh, make sure you wait until its all done and hit the download JSON (it downloads as a zip file)
8. With this zip file, unzip it however you choose
9. finally, run the /import_league command in your discord, the two required options are the following files: schedules.json and teams.json. Both of those are in the zip file
10. run the command, if you see `uploaded :)` then you are all set! if it fails, well contact me I will see what goes wrong :)
