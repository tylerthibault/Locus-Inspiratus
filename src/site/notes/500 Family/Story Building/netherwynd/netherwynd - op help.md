---
{"dg-publish":true,"permalink":"/500-family/story-building/netherwynd/netherwynd-op-help/","dgPassFrontmatter":true}
---


# Command block/terminal Arguments
| name | description | Example | Notes |
| ---- | ---- | ---- | ---- |
| name | the name of the item | name="tyler" |  |
| type | the type of the item | type="player" |  |
| r | radius | r=2 | radius gets from the middle of the block to the middle. Therefore items at 2 blocks away will not be effected if r=2 |
| rm | inverse radius | rm=2, r=4 | gets everything outside 2 radius but inside 4 radius |
| m | game type | m=s | m = game type and s = survival |
| c | choose | c=3, r=4 | choose 3 out of 4 radius. This will pick only three items even if there is 4 that it could grab. The 3 that it will choose will be random |
| l | less level | l=3 | only works with players. L=3 means players with 3 or less levels |
| lm | more levels | lm=3 | only works with players. lm=3 means players with 3 or more levels |
| x,y,z | places the source of the action | tp @e[x=-7, y=4, z=47] \~\~1\~ |  |
| tag | a tag that is on a person or thing | tp @e[tag=something] \~\~1\~ | FYI you can add a tag by running the command `tag @s add something` |

# Slash Commands
| **Command** | **Action** |
| ---- | ---- |
| /ability | Grants or revokes ability to a player |
| /alwaysday | Stops or resumes the day-night cycle |
| /camerashake | Creates a camera shaking effect |
| /changesetting | Change a dedicated server setting |
| /clear | Clear item(s) from the player's inventory |
| /clearspawnpoint | Removes the spawn point |
| /clone | Copies block(s) and puts them in a location |
| /connect | Connect to websocket server |
| /deop | Takes operator status away from a player |
| /dialogue | Opens NPC dialogue |
| /difficulty | Sets the game's difficulty |
| /effect | Add/Remove status effects |
| /enchant | Enchants a selected item |
| /event | Triggers an event |
| /execute | Executes a different command |
| /fill | Fills an area with blocks |
| /fog | Changes fog settings |
| /function | Runs a function |
| /gamemode | Sets player’s game mode |
| /gamerule | Sets game rule |
| /gametest | GameTest features |
| /give | Gives an item to a player |
| /help | Displays a list of available commands and information about them |
| /immutableworld | Set immutable world state |
| /kick | Kick a player |
| /kill | Kill any entity |
| /list | Lists players |
| /locate | Locate the closest structure |
| /me | Displays a message |
| /mobevent | Enables or disables mob event |
| /music | Allows the player to play music tracks |
| /op | Gives player operator status |
| /ops | Reloads or displays permissions list |
| /particle | Creates particle(s) |
| /playanimation | Play an animation |
| /playsound | Plays a sound |
| /reload | Reloads functions, advancements and loot tables |
| /replaceitem | Replace any item(s) in inventory |
| /ride | Change ride settings or entities |
| /save | Resume, status query, backup |
| /say | Displays a message to multiple players |
| /schedule | Schedule the execution of a function |
| /scoreboard | Manages the scoreboard |
| /setblock | Changes a block |
| /setmaxplayers | The max amount of players allowed to join |
| /setworldspawn | Sets the world spawn point |
| /spawnpoint | Set the spawn point of a player |
| /spreadplayers | Spreads entities around the map randomly |
| /stop | The command used to stop the server |
| /stopsound | Stop a sound |
| /structure | Save or load structures |
| /summon | Summons an entity |
| /tag | Control entity tags |
| /teleport | Teleports entities |
| /tellraw | Displays message to players (JSON) |
| /testfor | Number of entities matching specified criteria |
| /testforblock | Check if a block is in a location |
| /testforblocks | Check if the blocks in two regions match |
| /tickingarea | List, add, remove ticking areas |
| /time | Changes world time |
| /title | Control screen titles |
| /titleraw | Control screen titles (JSON) |
| /toggledownfall | Changes the weather |
| /tp | Same as '/teleport' |
| /w | Same as '/tell' ,'/msg'. Displays private message |
| /wb | Edit restricted blocks. Same as '/worldbuilder' |
| /weather | Sets the weather |
| /xp | Adds or removes exp from a player |