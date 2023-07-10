# ☁️ ElasticBungee ☁️ | Scale your infrastructure☁️ ElasticBungee ☁️ | Scale your infrastructure

# ElasticBungee
Synchronization of data between BungeeCord instances using Redis as data storage and as a message broker.

# Recomendate using update version by me: [Click here!](https://github.com/HappyRogelio7/InfinityElasticBungee)

### How does it work?
The plugin uses a Redis function that allows you to send messages and data in real time. This allows you to install the plugin on several BungeeCord instances, connect them to the same Redis server and have them synchronize their data.

Note: Do you want to know how DNS is configured so that a single domain redirects to several proxies to balance users? I have made [This Thread](https://www.spigotmc.org/threads/tutorial-how-to-have-multiple-bungeecord-instances-and-sync-them.530891/) that explains it.

Requirements:
A [Redis](https://redis.io/) Server

---

## Features

```
Synchronize player counter.
Block online players from connecting from another proxy.
Allows you to search which backend and proxy server a specific player is on.
Allow kicking players from different proxy instances.
Allows to send messages between all proxies.
Allow backend players to move between different proxy instances.
```

---

## Commands (Permission elasticbungee.use)

```
/eb broadcast <message> | Send a message to all proxies.
/eb find <player> | Search to which server a user is connected.
/eb kick <player> | Kick a player.
/eb ip <player> | Get a player's ip.
/eb send <player> <server> | Send a player to a server.
/eb sendall <source> <target> | Send all players from one server to another.
```

## To Do

API
Events
Maven Repository


The plugin is only in the first version. It is possible that it has bugs but I took care to test it as much as possible to avoid this. In any case, it is appreciated that if you find one, do not leave a negative review if you do not report it in the Issues section of GitHub.

If you have questions or need support, do not hesitate to enter our Discord server.

[Oficial Spigot](https://www.spigotmc.org/resources/%E2%98%81%EF%B8%8F-elasticbungee-%E2%98%81%EF%B8%8F-scale-your-infrastructure.97034/)
