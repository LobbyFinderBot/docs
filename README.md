## Quick Introduction:
> Do you have a Discord server? Are your users looking for a simpler way to open new text and voice lobbies on their own? Well, look no further our new Lobby Finder bot, will allow your community todo all of the above.

## Setup guide:
> **Automatic:** After inviting the bot, go into your bot-commands channel and run the command `$whitelist` in this very channel. By default every channel on the server is blacklisted from commands, so choose wisely, which channels you whitelist! Once you have whitelisted that channel run the automatic `$setup` command to finalize the setup of Lobby Finder bot.
> 
> **Manual:** If you don't want the bot to do all the work for you, run the setup command with the `-m` flag like this: `$setup -m`. The bot will then walk you through the setup process.
> 
> **Note:** The whitelist and setup commands requires you to have the `ADMINISTRATOR` permission. Make sure you have it.

## About:
> Our bot will help your discord server users connect with other users in a whole new way. This is the closest you will get to a party or lobby system directly in your Discord server. After inviting the bot and finishing its simple setup, users can create a lobby which creates a new voice and text channel. The new channels are only visible by anyone invited to the lobby by its owner or co-owner. 
> 
> Users are able to lock and unlock their lobby. They are able to join any open lobby using, and those lobbies get displayed in an automatically created channel. This is only scratching the surface of what our bot is capable of doing! So what are you waiting for, invite the bot into your server today!
> 
> Add Bot To Your Server: [INVITE NOW](http://invite.lobby-finder.com)

## Premium Version:
> Since the very beginning, we have been helping Discord server owners and users connect with one another in a whole new way. You can create text and voice channel lobbies directly in Discord without the need for a bunch of predefined channels for free.
> 
> To keep our bot and server updated as much as possible, we need developers, which can cost quite a bit of money. The bot also needs a hosting provider which is a monthly fee, so to combat this we have added in a few sweet features for our premium version of the bot. This is not required to use the bot, but it does give you a few extra perks which are listed below.
> 
> **Custom Lobby Names** - Users can change their lobby names using the name command inside their lobby.
> 
> **Custom Lobby Colors** - Users can change their lobby embed color using the color command inside their lobby.
> 
> **Global Lobby Linking** - Users can link their lobby to another lobby on your server or other premium servers from around the world.
> 
> **Lobby Limit Increase** - All lobbies will increase their maximum members allowed to 10 members for every new lobby.
> 
> **Custom Bot Colors** - Server owners can change the main embed color using the set command inside their server.
> 
> [UPGRADE NOW](https://www.patreon.com/lobbyfinder)

* All premium upgrades are intended for server owners to purchase for their own servers. If you are just looking to use the bot inside a server, it is absolutely free!

## Lobby Commands: [18]

> Command: `$color`
> 
> Description: Change the default color of your lobby.
> 
> Usage: $color`

> Command: `$ctl`
> 
> Description: Central Lobby control command.
> 
> Usage: $ctl -flag || To see available flags, run ctl -h

> Command: `$demote`
> 
> Description: Demote Lobby Members.
> 
> Usage: $demote @User

> Command: `$global`
> 
> Description: List all currently open lobbies on all servers.
> 
> Usage: $global || ctl -g

> Command: `$info`
> 
> Description: Return general information about your lobby, like members, creation date and ID. To get information about another user, use the whois command.
> 
> Usage: $info || ctl -i

> Command: `$invite`
> 
> Description: Invite other users to your lobby. They have to accept the invite before they will be added to your lobby
> 
> Usage: $invite @User

> Command: `$join`
> 
> Description: Send a join request to join another users lobby.
> 
> Usage: $join @User

> Command: `$kick`
> 
> Description: Kick members from your lobby.
> 
> Usage: $kick @User || ctl -k @User

> Command: `$link`
> 
> Description: Link your lobby to other lobbies on other servers.
> 
> Usage: $link <LOBBYID> || => Get the other lobby ID by doing ctl -g

> Command: `$list`
> 
> Description: Lobby list command. Returns an overview of all currently open lobbies on this guild.
> 
> Usage: $list | ctl -l

> Command: `$lock`
> 
> Description: Toggle the privacy setting of your lobby.
> 
> Usage: $lock/unlock || ctl -l

> Command: `$name`
> 
> Description: Rename your lobby.
> 
> Usage: $name <Newname>

> Command: `$owner`
> 
> Description: Transfer ownership to one of your lobby members.
> 
> Usage: $owner @User || ctl -o @User

> Command: `$lobby`
> 
> Description: Create a lobby and invite your friends.
> 
> Usage: $lobby - to create a lobby

> Command: `$promote`
> 
> Description: Promote a user to Co-Owner.
> 
> Usage: $promote @User || ctl -p @User

> Command: `$sudo`
> 
> Description: Lobby admin command. Use this to force add and remove users to and from lobbies. Also allows you to force close lobbies by ID.
> 
> Usage 1: $sudo -a -ID @User | Force add a user to a lobby.
> 
> Usage 2: $sudo -rm -ID @User | Force remove a user from a lobby.
> 
> Usage 3: $sudo -c -ID | Force close a lobby.
> 
> Usage 4: $sudo -l | List all open lobbies on this server.
> 
> Usage 5: $sudo -ul @User | Fetch Information about a certain user. Returns Lobby Name and ID.

> Command: `$unlink`
> 
> Description: Unlink your lobby.
> 
> Usage: $unlink

> Command: `unlock`
> 
> Description: Toggle the privacy setting of your lobby.
> 
> Usage: $lock/unlock | ctl -u

## System Commands: [11]

> Command: `$about`
> 
> Description: Show information about this Bot.
> 
> Usage: $about

> Command: `$ba`
> 
> Description: Manage open bugs.
> 
> Usage: $ba list, ba setactive ID, ba close ID

> Command: `$blacklist`
> 
> Description: Blacklist channels from commands.
> 
> Usage: $blacklist | Just run it in the channel that you want to add to the blacklist.

> Command: `$bug`
> 
> Description: Reports a bug to the developer(s).
> 
> Usage: $bug

> Command: `$help`
> 
> Description: Display available commands and their usage.
> 
> Usage: $help

> Command: `$inspector`
> 
> Description: Runs a check on your guild configuration and tells you what could be improved.
> 
> Usage: $inspector || sysctl -i

> Command: `$la`
> 
> Description: Returns your current permission level.
> 
> Usage: $la, || ctl -la

> Command: `$lobbymsg`
> 
> Description: Post an embed of open lobbies.
> 
> Usage: $lobbymsg <Channel ID>

> Command: `$reboot`
> 
> Description: Shuts down the bot. If running under PM2, bot will restart automatically.
> 
> Usage: $reboot

> Command: `$set`
> 
> Description: View or change settings for your server.
> 
> Usage: $set <setting> <value>

> Command: `$whois`
> 
> Description: Display information about a mentioned user.
> 
> Usage: $whois @someone

### Questions or need help?
> Check out our [Contact Us](https://github.com/LobbyFinderBot/lobbyfinderbot.github.io/wiki/Contact-Us) page for different ways of getting in touch.
