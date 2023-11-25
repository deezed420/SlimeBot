# Slime
Slime is a discord bot allowing you to create temporary voice channels with different features like locking, whitelists, kick and bans, and more.
## Setup
You can add Slime to your server by going to our [website](https://slimebot.vercel.app/) and clicking the use now button. After it is added, use the `/setup` command and go through the setup instructions. Be sure to use /setup in a place where no other users can tamper with the setup.

## Commands
Note that commands surrounded by ✨ are premium only.

### User Commands
These are commands that everyone can use.
| Command  | Arguments | Description |
| ------------- | ------------- | ------------- |
| `/room create`  | None  | Creates a room for the user with the default settings
| `/room title`  | <title>| Sets the room's title to the specified title
| `/room lock` | None | Locks the room so that no one can join
| `/room kick` | <user> | Kicks the selected user from the room
| `/room ban` | <user> | Bans the selected user from the room |
| `/room whitelist` | <state> | Sets the state of whitelist, if none then toggles state|
| `/room whitelist set` | <user1>...<user9> | Set the whitelist for the room |

### Admin Commands
These are commands only admins can use.
| Command  | Arguments | Description |
| ------------- | ------------- | ------------- |
| `/room nuke`  | None  | Destroys all rooms currently open
| `/room destroy`  | <room>| Destroys specified room
| `/room jtc` | <title> | ✨Creates a join-to-create voice channel with the title✨
| `/room halt` | <state> | Stops allowing rooms to be created specified by state
 


## Roadmap
- Add room dashboard for each user
- Add the only friends option
- Add website dashboard
