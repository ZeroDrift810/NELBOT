# snallabot

Snallabot is a one-stop-shop to help manage your madden league! It is an easy to use bot that handles the menial parts of running your league so you can focus on what matters most, running fun and succesful leagues. With game channels and team management, snallabot's goal is to make your life easy!

To setup the bot see the [setup instructions](setup.md). Need snallabot support? Join our [Discord](https://discord.gg/N5cTbEXrgq)!

## Commands

`/league_export` - messages the URL to type in the Madden exporter

`/game_channels create` - This creates game channels for that specific week. It will only create game channels for the regular season and it will create them under the configured category

`/game_channels clear` - this clears game channels under the configured category. it will not clear any channels that do not contain the word 'vs' so FW channels and such are OK

`/game_channels notify` - notifies each game channel to remind everyone to play their games. Optional parameter to just notify one channel

`/game_channels configure_notifier` - sets up snallabot notifier that will automatically track game channels

`/game_channels off_notifier` - turns off snallabot notifier.

`/game_channels configure` - sets the category to create/clear game channels

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

`/schedule` - shows the games scheduled for that week. Required `week` the week number (not playoffs)

`/logger configure` - configures snallabot logger for game channels. Optional `on` to turn it on and off, default to on

`/dashboard` - the link to open your snallabot dashboard

`/export current` - exports the current week through the snallabot dashboard

`/export week` - exports the specified week through the snallabot dashboard

`/export all_weeks` - exports the all weeks through the snallabot dashboard

Need snallabot support? Join our [Discord](https://discord.gg/N5cTbEXrgq)!
