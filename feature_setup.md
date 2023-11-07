# Setting up Snallabot features

## Setting up dashboard

Once the bot has been added to your discord do the following:

1. Run `/dashboard` to open your snallabot dashboard
2. Follow the directions to connect your league to snallabot. Let me know if you have any issues doing so
3. Once you reach your dashboard, you are all set up.
4. [Optional] Add more bot export links by clicking the `Add Export` button. Once you add the Url, make sure you check the right exports and hit the check mark to confirm!
5. The dashboard is all setup to use! Auto exporting is on for all the exports that have that option checked

Auto Export works in the following situations:

1. When you do `/game_channels clear` it will export the week that was advanced
2. When you are using snallabot game channel tracking, everytime the channel is cleared it exports the current week
3. If you are doing `/game_channels create` it will export the current week if it does not have the information for that week

So the recommendation is to advance the league in Madden, then do your `/game_channels clear` and `/game_channels create` to make sure it exports all your results from the previous week!


## Setting up teams

Snallabot provides an easy interface to assign teams for your league. 

1. first run `/teams configure` with the channel you would like to display the teams in and if you would like automatic role tracking
2. if you are using automatic role tracking, create a role for every team in the league. Otherwise, proceed to the next step
3. assign every team to a user using `/teams assign` supplying the team, the user, and optional role to track on (if you did step 2)
4. You are now setup to use teams!
5. use `/teams open` with the team name, city, or abbreviation to free a team

if you run into permission issues, snallabot should let you know. Make sure snallabot can send messages in the channel you provide in step 1. Snallabot will also need to server member permissions to read users and roles. 

## Setting up game channel tracking

1. first run `/game_channels configure notifier` with the fw channel, the amount of hours you would like snallabot to wait before reminding user to schedule their game, and an optional admin role for fw confirmations
2. run `/game_channels notify` to start game channel management!
3. [Optional] Want to save your game channels? Turn on snallabot logger! run `/logger configure` with the channel you want to output the game channel logs in. This might be noisy so be careful!

Snallabot wil need create channel, edit channel, create message, and server member permissions to track game channels. 

## Setting up stream counts

1. first run `/streams configure` with the stream channel you would like to post the counts in
2. you can now start counting streams with `/streams count` with the user who streamed!
