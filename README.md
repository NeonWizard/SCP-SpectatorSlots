**!!!UNFINISHED PROJECT!!!**
# SpectatorSlots
SpectatorSlots allows extra players to join the server and essentially wait in spectator mode until normal slots open up, at which point they will be able to participate in the game. No more spamming the connect button!

# Installation
**[Smod2](https://github.com/Grover-c13/Smod2) must be installed for this to work.**

1. Place the "SpectatorSlots.dll" file in your server's `sm_plugins` folder.
2. Increase your server slots by the amount of queued-spectator slots you want to have.
3. Set the `sslots_player_threshold` config variable to the amount of queued-spectator slots.

# Features
* Configurable amount of spectator slots.
* Ability to have queued spectators muted to avoid voice channel spam.

# Configuration
Config Option | Value Type | Default Value | Description
--- | :---: | :---: | ---
sslots_mute_waiting | Bool | False | Whether to mute queued spectators waiting to join the game.
sslots_player_threshold | Int | -1 | The amount of players allowed to actively play the game. -1 essentially disables the plugin, allowing all connected players to play.

*Note that all configs should go in your server config file, not config_remoteadmin.txt

### Place any suggestions/problems in [issues](https://github.com/NeonWizard/SCP-SpectatorSlots/issues)!
