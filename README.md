# Get5 Event API Plugin

![GitHub release (latest by date)](https://img.shields.io/github/v/release/yannickgloster/get5_eventapi)

This sourcemod plugin sends [Get5 Event logs](https://github.com/splewis/get5/wiki/Event-logs) as a post request to a server set with the CVAR `get5_event_api_url`.

This plugin this plugin was built to work in conjuction with [Discord 10man Bot](https://github.com/yannickgloster/discord-10man) however it can be used for any other project.

#### CVARs
```
get5_event_api_url - Set's the server url to send the post request to
get5_event_api_available - Checks if the plugin is correctly loaded on the server
```

### Server Requirements

To use this plugin on your server, you must have the following:

- [Get5](https://github.com/splewis/get5)
- [SteamWorks](https://forums.alliedmods.net/showthread.php?t=229556)

### Build Requirements

To build the plugin, you must have the following:

- [Get5](https://github.com/splewis/get5)
- [SteamWorks](https://raw.githubusercontent.com/KyleSanderson/SteamWorks/master/Pawn/includes/SteamWorks.inc)
- [sm-json](https://github.com/clugg/sm-json)

#### Thanks To

Forked from [splewis'](https://github.com/splewis) [get5_apistats](https://github.com/splewis/get5/blob/master/scripting/get5_apistats.sp) plugin.
