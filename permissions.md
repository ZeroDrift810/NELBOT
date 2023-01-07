# What Permissions Snallabot needs

For those curious or rightfully scared what permissions snallabot needs here are all the answers! The following discord actions are what snallabot intends to do:

1. Create and delete channels
2. Send and edit messages in specific channels
3. React to messages
4. Get users and roles

These are the only things snallabot needs to function in your discord. The first three provide simple ease of use functionality and are basic permissions. The last is a sensitive permission that is understandable to be wary of. Snallabot uses a list of users and roles to track which user is assigned to which team. This is so that admins do not have to do this work and instead just assign a role to a user. Some key things to note:

- Snallabot does NOT save a list of users. Only saves a user id for who is the owner of that team in madden
- Snallabot does NOT send any data to anywhere else. We are in no business selling any data and will never be!
- Data is securely stored in Google Cloud Firestore. The only access is from Snallabot and myself
- All code is public on Github if you would like to verify this

## Can I delete my data

Yes you can. There is no command or operation for this to happen, you may contact me directly and I will immediately delete all your data. Again the only data stored is your user id, no information about your user is stored.
