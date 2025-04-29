# snallabot

Snallabot started as a one-stop-shop to help manage your madden league! It is an easy to use bot that handles the menial parts of running your league so you can focus on what matters most, running fun and successful leagues. Easy setup, game channels, team management, and youtube/twitch broadcasts are key features that make your life easy. 

Snallabot is a free Discord bot for anyone to use, and is expanding to be an open source solution to aid other developers in helping the Madden community. Snallabot makes no  profit so is completely reliant on your support! Join our [Discord](https://discord.gg/zbx7NB4PX7) to find out more information on how you can support Snallabot.


To setup the bot see the [setup instructions](setup.md). Need snallabot support? Join our [Discord](https://discord.gg/zbx7NB4PX7)!

## Commands

`/league_export` - messages the URL to type in the Madden exporter

`/game_channels create` - This creates game channels for that specific week. It will only create game channels for the regular season and it will create them under the configured category, you can override the category with the optional parameter

`/game_channels clear` - this clears all your game channels

`/game_channels notify` - notifies each game channel to remind everyone to play their games

`/game_channels configure` - sets up the bot to do game channels

`/teams configure` - sets the channel to keep track of open teams

`/teams assign` - assigns a discord user to a team, updates the teams message immediately

`/teams open` - frees a team to be taken later, updates the teams message immediately

`/waitlist list` - lists the current waitlist

`/waitlist add` - adds the user to the waitlist. By default, this will add them to the end. Optional `position` will insert them into the position

`/waitlist remove` - removes the user from the waitlist

`/waitlist pop` - removes the top user from the waitlist. Optional `position` to remove a certain spot in the waitlist

`/waitlist notify` - notifies the top user in the waitlist. Optional `top` to specify how many users to notify at once.

`/streams configure` - configures the stream channel that the message will be tracked in

`/streams count` - counts the stream for a user (ups the count by 1). Optional `override` to set the count for that user

`/streams remove` - removes a user from the stream count

`/streams reset` - resets all users back to 0 streams **DANGER**

`/broadcasts configure` - configures the broadcast with the keyword to filter titles on, channel to display live streams, and an optional role to mention

`/broadcasts youtube add` - add a new youtube channel to watch broadcasts for

`/broadcasts youtube remove` - remove a youtube channel

`/broadcasts youtube list` - show your current youtube channels

`/broadcasts twitch add` - add a new twitch channel to watch broadcasts for

`/broadcasts twitch remove` - remove a twitch channel

`/broadcasts twitch list` - show your current twitch channels

`/schedule` - shows the games scheduled for that week. Required `week` the week number (not playoffs)

`/logger configure` - configures snallabot logger for game channels. Optional `on` to turn it on and off, default to on

`/dashboard` - the link to open your snallabot dashboard

`/export current` - exports the current week through the snallabot dashboard

`/export week` - exports the specified week through the snallabot dashboard

`/export all_weeks` - exports the all weeks through the snallabot dashboard

Need snallabot support? Join our [Discord](https://discord.gg/Dc9pTGg9Hc)https://discord.gg/Dc9pTGg9Hc!
