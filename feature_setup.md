# Setting up Snallabot features

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

Snallabot wil need create channel, edit channel, create message, and server member permissions to track game channels. 

## Setting up stream counts

1. first run `/streams configure` with the stream channel you would like to post the counts in
2. you can now start counting streams with `/streams count` with the user who streamed!

## Setting up broadcasts

1. first run `/streams broadcast configure` with the keyword for your league and the channel you want broadcasts in. Optional role for anyone to be mentioned
2. then add your channels with Youtube with, `/streams youtube add`

