# MatsuQueueBukkit
The bukkit plugin for MatsuQueue queue servers. See [MatsuQueueBungee](https://github.com/EmotionalLove/MatsuQueueBungee) for the Bungeecord companion plugin.

## About
This is an *optional* plugin for Bukkit/Spigot servers designated to be MatsuQueue queue servers. Depending on your needs and desires, you may desire this plugin. This plugin can help reduce load on your queue servers, and help keep a clean queue experience for your players.

# Default Configuration
```yml
## Note - Operators and users with the permission "matsuqueue.admin" will be excluded from restrictions. ##

forceLocation: true # Force the user to remain in a certain location.

forcedWorldName: "world_the_end" # the name of the world to force the user to remain in
forcedX: 0 # the coordinates that the user must remain at.
forcedY: 200
forcedZ: 0

hidePlayers: true # Hide players from eachother so that it looks like every user is alone in the world. This will also disable join/leave messages.
restrictMovement: true # Prevent players from moving.
forceGamemode: true # Force players to remain in a single gamemode
forcedGamemode: "spectator" # The gamemode to force players to remain in.
disableChat: true # Restrict players from chatting.
```

# Pre-made Queue World
If you want a simple pre-made queue world that features a "screensaver", check out the world in this github repo [here]()