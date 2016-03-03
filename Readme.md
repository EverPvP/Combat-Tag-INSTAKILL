Opdateret version af Combat-Tag-Instakill

# CombatTag:


Combat tag is a plugin for bukkit which prevents pvp loggers from getting away with logging.
This plugin was originally created by marinating. Trc is the old manager. EverPvP is currently managing this version of the plugin.



## Config file explanation:

- **disabledWorlds**: Worlds which will not spawn NPCs.
- **Tag-Duration**: Amount of seconds for a combat tag to last.
- **disabledCommands**: Commands which are disabled while in combat. Example: [/warp,/home,/spawn]
- **Enable-Debugging**: Debug mode on/off
- **Version**: Version of the plugin. DO NOT TOUCH THIS!
- **blockEditWhileTagged**: Whether people can edit blocks while tagged or not.
- **tagMessageDamaged**: Allows server owners to set custom tag messages. Sent to attacked person. [player] is replaced by player who hit them.
- **commandMessageTagged**: Allows server owners to set the custom message for the /ct command. [time] is replaced with the time left for the tag.
- **commandMessageNotTagged**: Allows server owners to set the custom message for the /ct command when a player is not tagged.
- **sendMessageWhenTagged**: When set to true, sends tagMessageDamaged to both players when they become tagged.
- **blockTeleport**: When set to true, blocks teleports caused by plugins (BEWARE, THIS ALSO MAKES IT SO OTHERS CAN'T TP THE PERSON AWAY EITHER)
- **tagMessageDamager**: Sent to attacker. [player] is replaced with the player they hit.
- **DropTagOnKick**: When set to true, will cause players to stop being tagged when they get kicked from the server.
- **blockEnderPearl**: When set to true, will block ender pearl teleports when tagged.
- **onlyDamagerTagger**: When set to true, will only tag the attacker and not the person who is hit.
- **blockCreativeTagging**: When set to true, will block people in creative mode tagging other players.
- **blockFlying**: When set to true, will disable flight while a player is tagged.
