# snallabot

A discord bot to manage your madden leagues! To setup the bot see the [setup instructions](setup.md).

## Commands

`/league_export` - messages the URL to type in the Madden exporter

`/game_channels create` - This creates game channels for that specific week. It will only create game channels for the regular season and it will create them under the configured category

`/game_channels clear` - this clears game channels under the configured category. it will not clear any channels that do not contain the word 'vs' so FW channels and such are OK

`/game_channels notify` - notifies each game channel to remind everyone to play their games. Optional parameter to just notify one channel

`/game_channels configure` - sets the category to create/clear game channels

`/teams configure` - sets the channel to keep track of open teams

`/teams assign` - assigns a discord user to a team, updates the teams message immediately

`/teams open` - frees a team to be taken later, updates the teams message immediately

`/import_league schedules teams` - *OBSOLETE SOON TO BE DELETED* imports the league into the bot. This only has to be done once per season! If you do it multiple times nothing bad happens tho! so if you want to update every playoff week that is okay

`/create_game_channels week category` - *OBSOLETE SOON TO BE DELETED* This creates game channels for that specific week. It will only create game channels for the regular season and it will create them under the desired category

`/clear_game_channels category` - *OBSOLETE SOON TO BE DELETED* this clears game channels under a category. it will not clear any channels that do not contain the word 'vs' so FW channels and such are OK

**Not Game channels do not work in playoffs yet!e**